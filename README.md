# Word dice

A nodejs lib to generate a random word (with true randomness) in the given language iso language eg (en-US, pt-PT)
Works on nodejs version v15.x or latter

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

- en-US
- it-IT
- pt-PT
- pt-BR
- pl-PL

##

Inspired by: https://www.npmjs.com/package/random-words
