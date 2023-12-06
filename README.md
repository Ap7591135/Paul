const { levanterTimeout } = require('../lib/')

/*

{

    pattern: 'Lyfe Bot Best Lol ?(.*)',

    fromMe: true,

    desc: 'auto about',

    type: 'bot',

},*/

const time = 60 * 1000 * 1 // 1 minute gap

const about = async () => {

  return 'Kithyoma🤖. ↪️'+new Date().toLocaleDateString()+' , ⏰ '+new Date().toLocaleTimeString('HI', { timeZone: 'Africa/Nairobi' }) + ' ❭  '

}

levanterTimeout(about, time)
