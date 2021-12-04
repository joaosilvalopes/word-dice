# Word dice

A lib to generate a random word in the given language iso language eg (en-US, pt-PT)

## Contributing

* 1st - Check an english word in the `/data/en-US` data file that you know a good one word translation for in a `lang` eg: (`pt-PT`)
* 2nd - Create a branch named `<lang>_<word>_<translation>` with one commit `<lang>_<word>_<translation>` eg: (`pt-PT_am_sou`)
* 3nd - Change the word in the corresponding line in the `/data/<lang>`
* 4rd - Change the word in the actual program `index.js` in `words[<lang>]`
* 5th - If the above steps were followed correctly approval is expected, tyvm :)

## Usage

```
npm i 'word-dice';

import wordDice from 'word-dice';

const word = rollDice.roll({
  minLength: 3,
  maxLength: 8,
  lang: 'en-US'
});

```
## Supported languages

* en-US
* it-IT
* pt-PT
* pt-BR
* pl-PL

## Inspired by: https://www.npmjs.com/package/random-words
