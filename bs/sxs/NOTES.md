1. Install express generator
1. run `npx express --view=pug`
1. if that does not work, install __Pug__ and change  
1. Install Bootstrap, jQuery, __not Popper__.
1. Add static routes 
```js
app.use(express.static(path.join(__dirname,".node_modules", "bootstrap", "dist", "js")));
app.use(express.static(path.join(__dirname, ".node_modules", "bootstrap", "dist", "css")));
app.use(express.static(path.join(__dirname, ".node_modules", "jquery", "dist")));```
