# khanhbaochau12.github.io
npm install -g create-react-app
create-react-app demo-deploy-github-pages

git init

git add .
 

git commit -m 'first commit'
 
git remote add origin https://github.com/khanhbaochau12/khanhbaochau12.github.io

git push origin master
	
npm install --save gh-pages


"homepage": "https://github.com/khanhbaochau12"

"predeploy": "npm run build",
"deploy": "gh-pages -d build",

npm run deploy
