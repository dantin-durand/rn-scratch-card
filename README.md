# rn-scratch-card

it's a fork of rn-scratch-card by @avegrv. On this version, you have access complete access of grid data.

![Scratch Sample](https://github.com/sweatco/rn-scratch-card/raw/main/demo.gif)

Check out it on [dribble](https://dribbble.com/shots/17396594-Sweatcoin-Scratch-The-Prize-Feature-Lottery-Style).

## Installation

```sh
yarn add @golden_vinyle/rn-scratch-card
```

[![https://nodei.co/npm/@golden_vinyle/rn-scratch-card.png?downloads=true&downloadRank=true&stars=true](https://nodei.co/npm/@golden_vinyle/rn-scratch-card.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/@golden_vinyle/rn-scratch-card)

## Usage

```js
import { ScratchCard } from 'rn-scratch-card'

// ...
<ScratchCard
  source={require('./scratch_foreground.png')}
  brushWidth={50}
  onScratch={handleScratch}
  style={styles.scratch_card}
/>
```

## Example project setup

```sh
cd rn-scratch-card
yarn install
cd example
yarn install
yarn run react-native run-ios
```

If you are launching project under iOS, please, also remember to

```sh
cd ios
pod install
```

## Contributing

See the [contributing guide](CONTRIBUTING.md) to learn how to contribute to the repository and the development workflow.

## License

MIT
