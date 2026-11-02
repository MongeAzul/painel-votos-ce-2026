# Painel de votos · Ceará 2026

Painel com os votos de candidatos no 1º turno de 2026 no Ceará, do estado à seção eleitoral, com comparação entre candidatos, quociente eleitoral e acompanhamento de metas.

**Acesso restrito.** O `index.html` abre numa tela de login. O conteúdo do painel está criptografado (AES-256, chave derivada da senha com PBKDF2-SHA256) e só é decifrado no navegador de quem entra com e-mail e senha autorizados.

Endereço: https://mongeazul.github.io/painel-votos-ce-2026/

## Atualização

O modelo, os dados e a lista de acessos ficam fora deste repositório, no computador do responsável. Para publicar uma versão nova:

1. Rode `.\build.ps1` na pasta do projeto. Ele gera um novo `index.html` já criptografado.
2. Aqui no GitHub, clique em **Add file › Upload files**, envie o `index.html` e clique em **Commit changes**.
3. O GitHub Pages atualiza em 1 a 2 minutos. Cada versão nova pede login de novo a todos.
