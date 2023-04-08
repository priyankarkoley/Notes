# Follow the steps to host any react app in GitHub Pages

<br>

## 1st Step

Make a repo on GH, and push all your bundle

<hr>

## 2nd Step

At package.json add

```
"homepage": "https://priyankarkoley.github.io/{name of repo}"
```

<hr>

## 3rd Step

Run

```
npm install gh-pages --save-dev
```

<hr>

## 4th step

At package.json, at SCRIPTS: add

```
"predeploy" : "npm run build",
"deploy" : gh-pages -d build",
```

<hr>

## 5th Step

Run at terminal

```
npm run deploy
```

<hr>

## And viola, it's done! Happy Hosting..!!
