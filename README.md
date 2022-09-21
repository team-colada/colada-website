# Setting up
Clone the Main branch of this repo
```
npm install
```
To enter development mode:
```
npm run dev
```
To build for production:
```
npm run build
```
Note: if you want to preview your built project:
```
npm run preview
```
# Deployment to gh-pages
While in the Main branch
```
git add . 
git commit -m "<commit message>"
git push

sh deploy.sh
```