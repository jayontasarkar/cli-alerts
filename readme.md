<h4 align="center">
Cross platform CLI Alerts with colors & colored symbols for success, info, warning, error.
<br>
Work on macOS, Linux, and Windows.

[![Follow @jayontasarkar on Twitter](https://img.shields.io/badge/FOLLOW%20@JAYONTASARKAR%20%E2%86%92-gray.svg?colorA=6A788D&colorB=6A788D&style=flat)](https://twitter.com/jayontasarkar/)

</h4>

<br>

# cli-alerts

## Install

```sh
npm install js-cli-alerts
```

## Usage

```js
const alert = require('js-cli-alerts');

// Provide the type, msg, and name options.
alert({type: `success`, msg: `Everything finished!`});
// Prints: ✔ SUCCESS Everything finished!

alert({type: `success`, msg: `Everything finished!`, name: `DONE`});
// Prints: ✔ DONE Everything finished!

alert({type: `warning`, msg: `You didn't add something!`});
// Prints: ⚠ WARNING You didn't add something!

alert({type: `info`, msg: `Awais is awesome!`});
// Prints: ℹ INFO Awais is awesome!

alert({type: `error`, msg: `Something went wrong!`});
// Prints: ✖ ERROR Something went wrong!
```

## API

### alert(options)

#### ❯ options

Type: `object`<br>
Default: `{}`

You can specify the options below.

##### ❯ type

Type: `string`<br>
Default: `error`

##### ❯ msg

Type: `string`<br>
Default: `You forgot to define all options.` (Error message)

##### ❯ name

Type: `string`<br>
Default: `''` (Empty string)

## Changelog

[❯ Read the changelog here →](changelog.md)

<br>

<small>**KEY**: `📦 NEW`, `👌 IMPROVE`, `🐛 FIX`, `📖 DOC`, `🚀 RELEASE`, and `🤖 TEST`

> _I use [Emoji-log](https://github.com/jayontasarakr/Emoji-Log), you should try it and simplify your git commits._

</small>

## License & Conduct

-   MIT © [Jayonta Sarkar](https://twitter.com/jayontasarkar/)
-   [Code of Conduct](code-of-conduct.md)

## Connect

<div align="left">
    <p><a href="https://github.com/jayontasarkar"><img alt="GitHub @jayontasarkar" align="center" src="https://img.shields.io/badge/GITHUB-gray.svg?colorB=6cc644&style=flat" /></a>&nbsp;<small><strong>(follow)</strong> To stay up to date on free & open-source software</small></p>
    <p><a href="https://twitter.com/jayontasarkar/"><img alt="Twitter @jayontasarkar" align="center" src="https://img.shields.io/badge/TWITTER-gray.svg?colorB=1da1f2&style=flat" /></a>&nbsp;<small><strong>(follow)</strong> To get #OneDevMinute daily hot tips & trolls</small></p>
    <p><a href="https://www.linkedin.com/in/jayontasarkar/"><img alt="LinkedIn @jayontasarkar" align="center" src="https://img.shields.io/badge/LINKEDIN-gray.svg?colorB=0077b5&style=flat" /></a>&nbsp;<small><strong>(connect)</strong> On the LinkedIn profile y'all</small></p>
</div>

## Sponsor

Me ([Jayonta Sarkar](https://twitter.com/jayontasarkar/)) who fell in love with open source. If you or your company use any of my projects or like what I’m doing then consider backing me. I'm in this for the long run. An open-source developer advocate.

[![Me on Twitter](https://img.shields.io/twitter/follow/jayontasarkar.svg?style=social&label=Follow%20@jayontasarkar)](https://twitter.com/jayontasarkar/)
