# koa-study

1.安装，使用koa，写一个简单的hello koa，并且运行它

const Koa = require('koa')
const app = new Koa()

app.use( async ( ctx ) => {
    ctx.body = 'hello koa2'
})

app.listen(3000)
console.log('[demo] start-quick is starting at port 3000')