# HexMMO — Base de dados

Site estático em português, pronto para publicar no GitHub Pages. A página está em `index.html` e as imagens usadas pelo site estão em `assets/`. Não é necessário instalar dependências nem configurar um servidor.

## Publicar no GitHub Pages

1. No GitHub, crie um repositório **público** e vazio para este projeto. Não marque as opções para adicionar README, `.gitignore` ou licença.
2. Adicione o repositório remoto e envie os arquivos deste projeto:

   ```powershell
   git remote add origin https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git
   git push -u origin main
   ```

   Troque `SEU-USUARIO` e `NOME-DO-REPOSITORIO` pelos valores reais do seu GitHub.
3. No repositório, abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**; selecione a branch `main` e a pasta `/(root)`, depois salve.
5. Aguarde o GitHub publicar. O endereço será `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

O repositório público deixa os arquivos do projeto visíveis para qualquer pessoa. Para publicar atualizações, envie as alterações para a branch `main`; o Pages atualizará o site automaticamente.
