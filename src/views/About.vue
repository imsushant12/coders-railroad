<template>
  <div class="about">
    <h1><router-link to="/">&laquo; GO BACK 🚂</router-link></h1>
    <p>
      This is a simple project made for
      <a href="https://hacktoberfest.digitalocean.com/" target="_blank"
        >Hactoberfest</a
      >. An easy entry to Pull Requests.<br />You can add your cart to the HF
      train by submitting a PR.<br /><br />
      ## How to contribute?<br />
      1. Fork repo<br />
      2. Clone your fork<br />
      3. Run `yarn`<br />
      4. Add your cart to `src/assets/data.json` and run `yarn serve` to see
      your cart<br />
      5. Run `yarn test:unit`<br />
      6. Create your branch, commit, push, create pull request
    </p>
    <pre>

```json
{
  "name": "YasiOnFire", // your Github name
  "text": "Yasio", // your message (max 22 chars)
  "cart": 1 // one of four avaiable carts, see below
}
```

### Avaiable carts:
```
__.oO.oOo.oOo.oOo.__ 
|                  | 
|        #0        | 
"OO--------------OO"=
                      
_____________________ 
|                   | 
|        #1         | 
"OO---------------OO"=
  ________________
 |                |  
 |                |  
_|       #2       |_ 
"OO--------------OO"=
      _________
 ____||_______||____
|                   |
|_       #3        _|
"OO---------------OO"=

.                     .
|         #4          |
"OO-----------------OO"=

_-_-_-_-_-_-_-_-_-_-_-_
|                     |
|         #5          |
"OO-----------------OO"=

_______________________
\                     /
 |        #6         |
"OO-----------------OO"=
```

### Rules

* only data.json may be edited
* must pass tests
* only one cart per github user 
* text may contain only letters and digits should be maximum of 22 chars
* must comply with the code of conduct

---

Made with [Vue](<a href="https://github.com/vuejs/vue" target="_blank">https://github.com/vuejs/vue</a>) 💚.
Inspired by [Twilio Open Pixel Art](<a href="https://open-pixel-art.com/" target="_blank">https://open-pixel-art.com/</a>).
    </pre>
  </div>
</template>

<style lang="scss">
.about {
  widows: 100%;
}
</style>
