# Word dice

A lib to generate a random word in the given language iso language eg (en-US, pt-PT)

## Usage

```
npm i 'word-dice';

import wordDice from 'word-dice';

const word = wordDice.roll({
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

##

Inspired by: https://www.npmjs.com/package/random-words
