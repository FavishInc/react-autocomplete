React Autocomplete
==================

Accessible, extensible, Autocomplete for React.js.

Docs coming soon, for now just look at the `propTypes` and examples :)

Trying to settle on the right API, and then focus hard on accessibility,
there are a few missing bits right now.

Stuff we need help with:

- mobile support verification generally
- default mobile styles/positioniong (you'll notice the styles are
  pretty lean, on purpose, apps should style this however they'd like)
- tests (eventually)

Favish Add-ons
--------------
This repo combines:
- The forked version of React Autocomplete which added the ability to pass an onBlur event handler (https://github.com/ejbyne/react-autocomplete) as mentioned in the following issue: https://github.com/rackt/react-autocomplete/pull/54
- The changes referenced in the fork that takes the input value as a prop and does not save it to state (https://github.com/CMTegner/react-autocomplete/commit/9c5ca43b96148be77b8363ca5461dcfd6d959726). This is referenced in the following issue: https://github.com/rackt/react-autocomplete/pull/65. This is pertinent in order to dynamically set the value of the input.
- Finally, use rackt-cli to execute `rackt build`. See more info here: https://www.npmjs.com/package/rackt-cli
