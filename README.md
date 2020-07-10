# MTG Card Render Bot

Magic the Gathering™ rendering chatbot for Facebook Messenger and Telegram.

## Content

- [Usage](#usage)
  * [Facebook Messenger](#facebook-messenger)
  * [Telegram](#telegram)
- [Basic examples](#basic-examples)
  * [1. Single card](#1-single-card)
  * [2. Single card from a specific set](#2-single-card-from-a-specific-set)
  * [3. Specific card from a specific set](#3-specific-card-from-a-specific-set)
  * [4. Random cards](#4-random-cards)
- [Advanced examples](#advanced-examples)
  * [1. Two cards, side by side](#1-two-cards-side-by-side)
  * [2. Two-cards combo](#2-two-cards-combo)
  * [3. Two-cards battles](#3-two-cards-battles)
  * [4. Three, four and five cards hands](#4-three-four-and-five-cards-hands)

## Usage

### Facebook Messenger

1. Open Facebook Messenger
2. Start a new discussion either by navigating to https://m.me/108575720841085 or by scanning this qrcode
<img src="media/qrcode_messenger.png" alt="https://m.me/108575720841085" />
3. Press `Get Started` button

### Telegram

1. Open Telegram
2. Start a new discussion either by navigating to https://t.me/cardrenderbot, searching for @cardrenderbot or by scanning this qrcode
<img src="media/qrcode_telegram.png" alt="https://t.me/cardrenderbot" />
3. Press `Start` button

## Basic examples

### 1. Single card

You can render a single card by typing either it's full name:

**💡 Example :** `sol ring`

<img src="media/examples/sol_ring.jpg" alt="sol ring" width="363" />

or part of it's full name if there's no ambiguity:

**💡 Example :** `wrath god`

<img src="media/examples/wrath_of_god.jpg" alt="wrath of god" width="363" />

### 2. Single card from a specific set

If you want to render a card from a specific set, you can prefix the name with the set code:

**💡 Example :** `mps sol ring` (will render Sol Ring from the _Kaladesh Inventions_ set)

<img src="media/examples/mps_sol_ring.jpg" alt="mps sol ring" width="363" />

### 3. Specific card from a specific set

Some sets contain cards with different illustrations. If you want a specific card, you can specify the set code and the collector number:

**💡 Example :** `und forest` (will render the basic Forest from the _Unsanctioned_ set, collector number 95)

<img src="media/examples/und_forest.jpg" alt="und forest" width="363" />

**💡 Example :** `und 96` (will render the full art Forest from the _Unsanctioned_ set, collector number 96)

<img src="media/examples/und_96.jpg" alt="und 96" width="363" />

### 4. Random cards

The chatbot can also rander random cards. To do that, you still have to guide it through the kind of card you are looking for.

**💡 Example :** `🤴` (will render a random legendary creature)

**💡 Example :** `🤴 🧟` (will render a random legendary zombie creature)

Here is the list of all supported emojis:

#### 1. Supported types

| Emoji | Card Type |
|:-----:|:----:|
| 🤴 👸 | commander |
| ☄️ | sorcery |
| ⚡ | instant |
| 🐾 | creature |
| ✨ | enchantment |
| ❄️ 🥶 | snow |

#### 2. Supported subtypes

| Emoji | Type |
|:-----:|:----:|
| 🧟 | zombie |
| 🧙 | wizard |
| 🧛 | vampire |
| 🧜 | merfolk |
| 🧚 | faerie |
| 🧝 | elf |
| 🐒 🐵 | monkey|
| 🧞 | djinn |
| 🦖 🦕 | dinosaur |
| ⚔️ | warrior |
| 🐿️ | squirrel |
| 🕷️ | spider |
| 🐉 🐲 | dragon |
| 🐙 | octopus |
| 🦑 | kraken |
| 👼 | angel |
| 👻 | spirit |
| 👹 👿 😈 | demon |
| 👺 | goblin |
| 🐈 🐱 😺 | cat |
| 🐦 | bird |
| 🦀 | crab |
| 🐗 | boar |
| 🐍 | snake |
| ☠️ 💀| skeleton |
| 🌲 🎄 🌳 🌴 | treefolk |
| 🐻 | bear |
| 👁️ | homunculus |
| 🐋 🐳 | whale |
| 🦈 | shark |
| 🦊 | fox |
| 🐺 | wolf |

## Advanced examples

### 1. Two cards, side by side

If you want to render two cards, side by side, just type two queries on two lines:

**💡 Example :**\
`Thrasios, Triton Hero`\
`Tymna the Weaver`

<img src="media/examples/thrasios_tymna.jpg" alt="Thrasios Tymna" width="363" />

### 2. Two-cards combo

If you want to render a two-cards combo, you can seperate the two queries by the `+` sign:

**💡 Example :** `Demonic Consultation + Thassa Oracle`

<img src="media/examples/demonic_thassa.jpg" alt="Demonic Consultation + Thassa Oracle" width="363" />

### 3. Two-cards battles

If you want showcase a battle between two cards, you can seperate the two queries by the `vs` sign:

**💡 Example :** `Simic Signet vs Talisman of Curiosity`

<img src="media/examples/signet_vs_talisman.jpg" alt="Simic Signet vs Talisman of Curiosity" width="363" />

### 4. Three, four and five cards hands

If you want to render a hand of three, four or five cards, just type the queries on seperate lines:

**💡 Example :**\
`Mythos of Vadrok`\
`Mythos of Illuna`\
`Mythos of Nethroi`\
`Mythos of Brokkos`\
`Mythos of Snapdax`

<img src="media/examples/mythos_cycle.jpg" alt="Mythos cycle" width="363" />
