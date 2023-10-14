<h3>Euphyllia Multidevice (BETA VERSION)</h3>

![euphyllia-bot](https://telegra.ph/file/c9865d6872fb1f05e7c8a.jpg)

##

<h4>Apa itu euphyllia bot ?</h4>
<p>Euphyllia Bot adalah bot WhatsApp multi-device yang berasal dari script euphyllia button, lebih tepatnya euphyllia bot adalah versi mendatang (Beta) yang akan ditingkatkan dan menjadi versi stabil.</p>

##
<h>**config.js**</h2>

```javascript
// Script By Im-Dims??
// Credits, jangan dihapus atau diubah!

// - - Thanks To - -
// • Allah Swt
// • Wh Mods Dev
// • Xyroinee
// • Creator Rest Api
// • Dll

// [!] jangan lupa ganti ownernya

import { watchFile, unwatchFile } from 'fs'
import chalk from 'chalk'
import { fileURLToPath } from 'url'
import moment from 'moment-timezone'
import { group } from 'console'
import PhoneNumber from 'awesome-phonenumber'
/*============= WAKTU =============*/
let wibh = moment.tz('Asia/Jakarta').format('HH')
    let wibm = moment.tz('Asia/Jakarta').format('mm')
    let wibs = moment.tz('Asia/Jakarta').format('ss')
    let wktuwib = `${wibh} H ${wibm} M ${wibs} S`
    
    let d = new Date(new Date + 3600000)
    let locale = 'id'
    // d.getTimeZoneOffset()
    // Offset -420 is 18.00
    // Offset    0 is  0.00 
    // Offset  420 is  7.00
    let weton = ['Pahing', 'Pon', 'Wage', 'Kliwon', 'Legi'][Math.floor(d / 84600000) % 5]
    let week = d.toLocaleDateString(locale, { weekday: 'long' })
    let date = d.toLocaleDateString(locale, {
      day: 'numeric',
      month: 'long',
      year: 'numeric'
    })
    const more = String.fromCharCode(8206)
const readMore = more.repeat(4001)

//----------- Owner -----------//
global.owner = [
['6281398274790', 'Dims', true]
]
global.mods = []
global.prems = []
global.nomorbot = '6282113847022'
global.nomorown = '6281398274790'
global.nomorown1 = '6281398274790'
global.nomorown2 = '6281398274790'
global.nomorwa = '6285607265790'
//----------- Bot info -----------//
global.readMore = readMore
global.author = 'Dims'
global.namebot = 'Euphyllia - Multidevice'
global.wm = '© Euphyllia By Dims'
global.watermark = wm
global.wm2 = 'Euphyllia Bot'
global.botdate = `Date: ${week} ${date}\nTime: ${wktuwib}`
global.bottime = `Time: ${wktuwib}`
global.titlebot = `Euphyllia - MD`
global.stickpack = 'Euphyllia By'
global.stickauth = `© Dims`
global.week = `${week} ${date}`
global.wibb = `${wktuwib}`
global.nameown1= 'Dims'
global.nameown2 = 'Dims'
global.Linkgc = 'Bentar'
global.lynk = '-'
//----------- Link media sosial -----------//
//Link Social Media Ganti Aja Kalau Ga Punya Biarin Aja
global.sig = 'https://www.instagram.com/' //instagram
global.sgh = 'https://github.com/Im-Dims' //github
global.sgc = 'https://chat.whatsapp.com/CHVe6nOEBcw1aRamTnHQ4q' //group whatsapp
global.sdc = '-' //discord
global.syt = 'https://www.youtube.com/@Dims_senpai'
global.snh = 'https://www.youtube.com/@DimsT1943' //youtube
//----------- Donasi / payment -----------//
global.psaweria = 'https://saweria.co/'
global.ptrakterr = 'https://trakteer.id/'
global.pdana = '6282113847022' // dana
global.povo = '6281398274790' // ovo
global.pgopay = '-' // gopay
global.plinkaja = '-' //link aja
global.ppulsa = '-' // pulsa
global.ppulsa2 = '-' //pulsa 2
global.ListHargaSewa = '├ 5 Hari IDR 3.000\n├ 7 Hari IDR 5.000\n├ 15+5 Hari IDR 10.000\n├ 30 Hari IDR 15.000'
//----------- Tampilan -----------//
global.LyAtas1 = '•⟅━━━ ❨'
global.LyAtas2 = '❩'
global.Ly = '┃'
global.lybwh = '┗━━┈┈ ⳻⳻'
global.sym = '◈▻'
global.sym2 = '➭'
global.dmenut = 'ଓ═┅═━–〈' //top
global.dmenub = '┊↬' //body
global.dmenub2 = '┊' //body for info cmd on Default menu
global.dmenuf = '┗––––––––––✦' //footer
global.dashmenu = '❏ *DASHBOARD* ❏'
global.cmenut = '❏––––––『' //top
global.cmenuh = '』' //header
global.cmenub = '┊✦ ' //body
global.cmenuf = '┗━═┅═━––––––๑\n' //footer
global.cmenua = '\n⌕ ❙❘❙❙❘❙❚❙❘❙❙❚❙❘❙❘❙❚❙❘❙❙❚❙❘❙❙❘❙❚❙❘ ⌕\n     '
global.pmenus = '✦'
global.htki = '『' // Hiasan Titile (KIRI)
global.htka = '』' // Hiasan Title  (KANAN)
global.lopr = 'Ⓟ' //LOGO PREMIUM ON MENU.JS
global.lolm = 'Ⓛ' //LOGO LIMIT/FREE ON MENU.JS
global.htjava = '✦'    //hiasan Doang :v
global.hsquere = ['⛶','❏','⫹⫺']
// wait proses
global.stiker_wait = '_Sedang Di Proses, Mohon Tunggu_.....'
global.wait = '_Sedang Di Proses, Mohon Tunggu Sebentar_....'
global.eror = 'Terjadi Kesalahan Coba Lagi Nanti!'
global.multiplier = 69 // The higher, The harder levelup
global.rpg = {
  emoticon(string) {
    string = string.toLowerCase()
    let emot = {
      agility: '🤸‍♂️',
      arc: '🏹',
      armor: '🥼',
      bank: '🏦',
      bibitanggur: '🍇',
      bibitapel: '🍎',
      bibitjeruk: '🍊',
      bibitmangga: '🥭',
      bibitpisang: '🍌',
      bow: '🏹',
      bull: '🐃',
      cat: '🐈',
      chicken: '🐓',
      common: '📦',
      cow: '🐄',
      crystal: '🔮',
      darkcrystal: '♠️',
      diamond: '💎',
      dog: '🐕',
      dragon: '🐉',
      elephant: '🐘',
      emerald: '💚',
      exp: '✉️',
      fishingrod: '🎣',
      fox: '🦊',
      gems: '🍀',
      giraffe: '🦒',
      gold: '👑',
      health: '❤️',
      horse: '🐎',
      intelligence: '🧠',
      iron: '⛓️',
      keygold: '🔑',
      keyiron: '🗝️',
      knife: '🔪',
      legendary: '🗃️',
      level: '🧬',
      limit: '🌌',
      lion: '🦁',
      magicwand: '⚕️',
      mana: '🪄',
      money: '💵',
      mythic: '🗳️',
      pet: '🎁',
      petFood: '🍖',
      pickaxe: '⛏️',
      pointxp: '📧',
      potion: '🥤',
      rock: '🪨',
      snake: '🐍',
      stamina: '⚡',
      strength: '🦹‍♀️',
      string: '🕸️',
      superior: '💼',
      sword: '⚔️',
      tiger: '🐅',
      trash: '🗑',
      uncommon: '🎁',
      upgrader: '🧰',
      wood: '🪵'
    }
    let results = Object.keys(emot).map(v => [v, new RegExp(v, 'gi')]).filter(v => v[1].test(string))
    if (!results.length) return ''
    else return emot[results[0][0]]
  }
}
//-----------------------------------//
// Untuk apikey biarin aja pake ini aja kalau fitur error beli apikeynya jangan cuma nyolong aja:v
//----------- Apikey -----------//
global.dims = 'YOUR_KEY', // https://xzn.wtf/
global.xyro = 'YOUR_KEY', // https://api.xyroinee.xyz/
global.wibu = 'YOUR_KEY', // https://api.zahwazein.xyz/
global.keysxteam = 'YOUR_KEY',
global.keysneoxr = 'YOUR_KEY',
global.lolkey = 'YOUR_KEY', // https://lolhuman.xyz/
global.caliph = 'YOUR_KEY',
global.rose = 'YOUR_KEY',
global.xcoders = 'YOUR_KEY',
global.ibeng = 'YOUR_KEY',
global.botcahx = 'YOUR_KEY',
global.fgmods = 'YOUR_KEY',
global.org = 'org-VKTbfzIGL0EfLb8RgRfbLvbu', //openAI Organization name
global.deepai = 'quickstart-QUdJIGlzIGNvbWluZy4uLi4K', // https://deepai.org
global.uptime = '' // Masukin apikey uptimerobot kamu disini // https://uptimerobot.com/dashboard?ref=website-header#mySettings

global.APIs = {
  xteam: 'https://api.xteam.xyz',
  dzx: 'https://api.dhamzxploit.my.id',
  lol: 'https://api.lolhuman.xyz',
  neoxr: 'https://api.neoxr.my.id',
  zenzapis: 'https://api.zahwazein.xyz',
  akuari: 'https://api.akuari.my.id',
  akuari2: 'https://apimu.my.id',
  fgmods: 'https://api-fgmods.ddns.net',
  botcahx: 'https://api.botcahx.biz.id',
  ibeng: 'https://api.ibeng.tech/docs',
  rose: 'https://api.itsrose.site',
  popcat: 'https://api.popcat.xyz',
  xcoders: 'https://api-xcoders.site'

},
global.APIKeys = {
  'https://api.xteam.xyz': `${keysxteam}`,
  'https://api.lolhuman.xyz': `${lolkey}`,
  'https://api.neoxr.my.id': `${keysneoxr}`,
  'https://api.zahwazein.xyz': `${wibu}`,
  'https://api-fgmods.ddns.net': `${fgmods}`,
  'https://api.botcahx.biz.id': `${botcahx}`,
  'https://api.ibeng.tech/docs': `${ibeng}`,
  'https://api.itsrose.site': `${rose}`,
  'https://api-xcoders.site': `${xcoders}`
}
//----------- Thumbnail -----------//
global.dpptx = 'application/vnd.openxmlformats-officedocument.presentationml.presentation'
global.ddocx = 'application/vnd.openxmlformats-officedocument.wordprocessingml.document'
global.dxlsx = 'application/vnd.openxmlformats-officedocument.spreadsheetml.sheet'
global.dpdf = 'application/pdf'
global.drtf = 'text/rtf'
global.optsnsfw = true 
global.premnsfw = true 

// ganti aja kalau ga tau cara gantinya buka telegra.ph upload foto nya di situ terus salin link nya kesini
global.anu = 'https://telegra.ph/file/ec21bc2a370da6437ef89.jpg' // Thumbnail Kebutuhan doang:v
global.media = 'https://telegra.ph/file/02a8d3c4b00146bbfeb5d.jpg'
global.lia = 'https://telegra.ph/file/e7d41d136aff71921c0f5.jpg' // Foto Allfake
global.thumb = 'https://telegra.ph/file/3cdaaf791f4eeffe51416.jpg' // Foto Thumbnail Anu
global.imagebot = 'https://telegra.ph/file/771ec1b185f02be1e573e.jpg' // Foto Menu
global.giflogo = 'https://telegra.ph/file/3343a2dad0c4ffd3a44c6.mp4' // Foto Menu Gif
global.thumbs = ['https://telegra.ph/file/5adcb114b279c0085ac15.jpg'] // Foto Allfake 2
global.thumbnailUrl = ['https://telegra.ph/file/ef4b742d47e6a9115e2ff.jpg'] // Gambar Welcome 
global.fotonya1 = 'https://telegra.ph/file/7dff62656e734888dccad.jpg' // Foto Loli 
global.fotonya2 = ' ' 
global.fsizedoc = '9999999'
global.fpagedoc = '9999999'
global.thumbdoc = 'https://telegra.ph/file/5adcb114b279c0085ac15.jpg'
//-----------------------------------//

let file = fileURLToPath(import.meta.url)
watchFile(file, () => {
  unwatchFile(file)
  console.log(chalk.redBright("Update 'config.js'"))
  import(`${file}?update=${Date.now()}`)
})
```
##

<h4>Berapa harga script euphyllia bot?</h4>

- 🎗️ IDR **Rp 47.000** Free Update</b>

##

<h4>Bot Type</h4>

- <b>Plugins</b>
- ~Case~

##

**Manfaat**
- [x] Free update according to plan
- [x] Free [LoL Human REST APIs](https://api.lolhuman.xyz)
      
##

<h4>Dimana saya bisa membeli script euphyllia bot secara resmi ?</h4>

- [Whatsapp](https://wa.me/+6281398274790)
- [Telegram](https://t.me/euphy_ch)
- [Instagram](https://instagram.com/dims_t11)

##

<h4>Read this before purchasing the script</h4>

- Should I understand programming?
   - Yes, you should be able to master basic JavaScript & Node.js.

- Can I get a refund once I've received the script?
   - No, I do not accept refund requests.
 
- Are there any plugins that are encrypted?
   - Adding encryption to certain parts of the code in plugins, in order to prevent unauthorized transactions.

- Can I request a feature?
   - Yes, you are free to request any feature, but I may not necessarily develop it, though I will do my best.

- Is it possible to negotiate the price of the script?
   - No, I do not accept price negotiations.

- Can I get the script for free?
   - No, I do not provide the script for free

- How many times can I change my IP address?
   - You can change your IP address up to 5 times.

- When I have used all of my IP addresses, will there be a charge to obtain more IP slots?
   - Yes, you will incur an additional fee to obtain more IP slots. The cost for 1 IP slot is **Rp 15.000,00** / **$1**.

- Will I get the werewolf and blackjack features as well?
   - I'm sorry, I haven't published the werewolf and blackjack features yet.
 
- Which features do you encrypt?
   - I encrypted the **index.js**, **print.js**, and **viki-regmail.js** files **(97% Not Encrypted)**.

- Why did you encrypt the code?
   - I encrypted the code to prevent it from being sold, and the encrypted code doesn't contain any watermark within the text message.

- Am I allowed to share plugins, code, and bot api keys with others?
   - No, I strongly prohibit that.

##

<h4>The script is supported to run on:</h4>

- [x] Rdp
- [x] Vps
- [x] Railway
- [x] Panel Pterodactyl  
- [x] Replit
- [x] Optiklink 

##

Demo : [euphyllia bot](https://wa.me/6282113847022?text=.menu)
<br>
Creator : [Dims](https://wa.me/6281398274790)
<br>
Official Group : [Euphyllia Bot](https://chat.whatsapp.com/CHVe6nOEBcw1aRamTnHQ4q)

##

<h4>Latest changelog update</h4>

| ChangeLog | Published On |
| ----- | ------------ |
|  New feature, **Chat Bot** and **Character Ai** and **Auto download** ( tiktok/Instagram )| Minggu Agustus 22 2023 |
|  Update all fitur| Rabu Juli 19 2023|
|  Starting **Euphyllia bot version 1.0.0**| Rabu Juli 12 2023 |

