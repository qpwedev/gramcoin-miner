# [Gramcoin](https://gramcoin.org) Miner

## Setup

1. [Compile TON from sources](https://docs.ton.org/develop/howto/compile)
2. Navigate to your build folder (ton-build)

```bash
cd ton-build
```

3. Fill out all env variables (check .example.env)

```env
TONCENTER_API_KEY= "" # from https://t.me/tonapibot
TONCONSOLE_BEARER= "" # from https://tonconsole.com/dashboard

MY_ADDRESS = "UQAwtgXjB-Zl5MtMQPdW6BcqIGB0oTYhrSb8lsLFw0EOUJCs" # your wallet address v4
MINTER_ADDRESS = "EQDIDs45shbXRwhnXoFZg303PkG2CihbVvQXw1k0_yVIqxcA" # from https://gramcoin.org/Grams-HOWTO.txt

MNEMONIC = "bla bla bla" # 24 words
```

4. Run commands in terminal

```bash
pnpm i
npx ts-node main.ts

```

### For any questions contact me in Telegram @qpwedev
