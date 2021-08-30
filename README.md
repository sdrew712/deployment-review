# deployment-review


steps: 
1. npm init -y
2. npm i express
3. add "start": "node server/index.js" to package.json
4. add procfile
5. add server/index.js
6. add <link rel="stylesheet" href="/css"> to index.html
7. add app.use('/css', express.static(path.join(__dirname, '../index.css'))) to index.js
8. push to github
9. link to heroku