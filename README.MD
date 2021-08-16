This is a test project of [pdoc3](https://pdoc3.github.io/pdoc/) + [npm gh-pages](https://www.npmjs.com/package/gh-pages-cli)  capabilities.

**Step-1:-** Installing gh-pages packages
npm install gh-pages

**Step-2:-** create file name as package.json with below contents 
```
"scripts": {
  "deploy": "npm run gh-pages",
  "gh-pages": "gh-pages -d dist -b gh-pages"
}
```
**Step-3**:- Running the cmd to publish the gh-pages and after running the below cmd will need to give your github username and github personal token(not github password)
```
root@INSWL-B3V2273:~/pdoc3_test# **node node_modules/gh-pages/bin/gh-pages --dist html/**
```



