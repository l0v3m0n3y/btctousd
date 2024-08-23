# btctousd
JavaScript library for btc to usd convert 
# main
```js
async function main(){
    const {btctousd} = require('./btctousd');
    const btc= new btctousd();
    let req=await btc.btc_usd()
    console.log(req)
}
main()
```
