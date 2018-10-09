npm install -g @angular/cli

ng new ng06

ng serve --open

#npm install --save-dev electron
npm install --save-dev --save-exact electron@latest
npm install --save-dev --save-exact electron-builder@latest

npm run electron
npm run build-electron
npm run build-electron-aot

1. Init Repo (VSCode)

2. Commit Repo (VSCode)

3. Create Repo (GitHub REST API)
-> curl -u 'kwokhung' https://api.github.com/user/repos -d '{"name":"ng06"}'

4. Remote Add Origin
-> git remote add origin https://github.com/kwokhung/ng06

5. Push Origin Master
-> git push -u origin master
