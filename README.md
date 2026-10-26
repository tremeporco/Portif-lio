# Portfólio pessoal — Eduardo Passarelo

Site estático feito com HTML, CSS e JavaScript, responsivo e pronto para publicação no GitHub Pages.

## Antes de publicar
1. Abra `index.html` e substitua os links de contato na seção `#contato` pelo seu e-mail, GitHub e LinkedIn reais.
2. Confira as descrições dos projetos e ajuste qualquer detalhe que queira apresentar de outra forma.
3. Se possível, adicione links para os repositórios públicos e capturas de tela dos projetos.

## Testar localmente
Abra `index.html` no navegador. Para desenvolvimento, também pode usar a extensão Live Server do VS Code.

## Publicar no GitHub Pages
1. Crie um repositório público no GitHub, por exemplo `portfolio`.
2. Envie os arquivos `index.html`, `style.css`, `script.js` e `README.md` para a raiz do repositório.
3. No repositório, abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Selecione a branch `main` e a pasta `/ (root)`, depois clique em **Save**.
6. Aguarde a publicação. O endereço será parecido com `https://SEU-USUARIO.github.io/portfolio/`.

## Git (terminal)
```bash
git init
git add .
git commit -m "Cria portfólio pessoal"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/portfolio.git
git push -u origin main
```

Depois de publicar, o link do repositório e o link do GitHub Pages são os que você pode entregar.
