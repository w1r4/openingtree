# Openingtree
Code for [openingtree.com](https://www.openingtree.com). It downloads chess games in form of a pgn from any source, applies specified filters and constructs an openingtree. 
The tree is visualized on a chessboard. It also shows win percentages and other statistics with different moves

## Architecture diagram
This does not correlate one to one with the code modules but the interactions at a high level are depicted accurately.

![GitHub Logo](/docs/images/architecture.png)

## Run locally
```
yarn
yarn start
```
starts a server on port `3000`

if yarn start error.

Error: error:0308010C:digital envelope routines::unsupported

```
export NODE_OPTIONS=--openssl-legacy-provider
```

## Build for production
```
yarn build
```


