# Site Profissional — Dra. Michelli Ribeiro Pereira

Site estático desenvolvido para apresentação profissional da Dra. Michelli Ribeiro Pereira, Advogada OAB/PR 113.720.

## ✅ Como publicar no GitHub Pages

1. **Clone ou acesse o repositório** que você já criou no GitHub.
2. **Faça upload dos arquivos** deste projeto (basta o `index.html`) para a raiz do repositório.
3. Vá em **Settings → Pages** no repositório.
4. Em **Source**, selecione `Deploy from a branch`.
5. Selecione o branch `main` (ou `master`) e pasta `/ (root)`.
6. Clique em **Save**.
7. Aguarde ~1 minuto. O site estará disponível em:
   `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`

## 📦 Estrutura

```
index.html   → site completo (imagem e logo embutidos em base64)
README.md    → este arquivo
.nojekyll    → evita processamento Jekyll desnecessário
```

## 🔧 Personalizações futuras

| O que alterar | Onde no código |
|---|---|
| Foto principal | `src="data:image/jpeg;base64,..."` nas seções Hero e Sobre |
| Logo | Symbol SVG `#logo-mark` no início do `<body>` |
| Texto / conteúdo | Diretamente nas seções HTML |
| Cores | Variáveis CSS `:root` no início do `<style>` |
| Domínio personalizado | Criar arquivo `CNAME` com o domínio (ex: `michelliribeiro.adv.br`) |

## 📱 Recursos

- Design responsivo (mobile e desktop)
- Botão flutuante WhatsApp
- Formulário de contato (redireciona para WhatsApp)
- Animações suaves de scroll
- Logo monograma MR integrado
- Foto da advogada embutida

---
*Desenvolvido com HTML, CSS e JavaScript puro. Sem dependências de backend.*
