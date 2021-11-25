# Webpack zDobraMorda build

## Get progect
Go to console<br>
<git clone https://github.com/Fantasydart/webpack.git>

## First Commit
<git commit -m "first commit"><br>
<git branch -M main><br>
<git remote add origin https://github.com/Fantasydart/webpack.git><br>
<git push -u origin main><br><br><br>
…or push an existing repository from the command line<br>
<git remote add origin https://github.com/Fantasydart/webpack.git><br>
<git branch -M main><br>
<git push -u origin main><br>

## First steps in project
<npm init> - use params project name, as default webpack<br>
<npm i> - install `node_modules`<br>

Webpack commands(you can see in `package.json` in scripts)<br>
```javascript
 "scripts": {
    "build": "cross-env NODE_ENV=production webpack --mode production",
    "dev": "cross-env NODE_ENV=development webpack --mode development",
    "start": "cross-env NODE_ENV=development webpack serve --mode development"
}, 
```

<npm run build> - for production<br>
<npm run dev> - for development version<br>
<npm run start> - start live-server in http://localhost:3000/