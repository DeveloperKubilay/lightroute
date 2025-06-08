![Banner](https://raw.githubusercontent.com/YiitWT/lightroute/main/cdn/Logotextbanner.png)
# 🌩️ LightRoute

A ligth weight router module just like ExpressJS, it's easy to use and easy to understand and it's a good choice for beginners also professionals.

## 🗽 Features

- Easy to learn
- Every functions you need.
- Lightweight and fast as lightning
- Cross platform


## 📦 Installation

You can install LightRoute via NPM/YARN

```bash
npm install @kubilaytr/lightroute
yarn add @kubilaytr/lightroute
```

## Lets Start Building 🚀
```js
const lightroute = require("@kubilaytr/lightroute")
const app = new lightroute()

app.get("/", (req,res) => {
    res.text("Hello World!")
})

app.listen(80,function(){
    console.log("Listening 80")
})
```

![lightroute](https://raw.githubusercontent.com/DeveloperKubilay/lightroute/refs/heads/main/cdn/image.png)
    
## 🚀 Documentation
You can learn how to use it from GitBook

[Documentation](https://lightroute.gitbook.io/)


## 📰 License

[Apache 2.0](https://choosealicense.com/licenses/apache-2.0/)


## 🫅 Authors

- [@YiitWT](https://www.github.com/YiitWT)
- [@DeveloperKubilay](https://www.github.com/developerkubilay)
