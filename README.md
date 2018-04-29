# JavaScript Library Starter

## Installation

```
git clone https://github.com/ChangJoo-Park/js-library-starter.git
cd js-library-starter
npm install
```

## REPL

js-library-start support REPL(Read Eval Print Loop). You can test library with interactive command-line interface.

![Imgur](https://i.imgur.com/hCLezRc.gif)

```
npm run repl

> lib.sum(1,2)
# Ctrl + D for Quit
```

edit `.replrc.js` for specific options.

thanks, [local-repl](https://www.npmjs.com/package/local-repl)


## Testing

```
# for one time testing
npm run test

# for watching file changes
npm run test:watch
```

If using Visual Studio Code, you can interactive testing with debugger.
[Jest](https://marketplace.visualstudio.com/items?itemName=Orta.vscode-jest) for vscode plugin here.

![image](https://i.imgur.com/72z5Tq7.gif)


## Development

```
npm run dev
```

## Build

```
npm run build
```

## Publish

First, change all properties iside package.json for your libs.

and..

follow this [publish npm package guide](https://docs.npmjs.com/getting-started/publishing-npm-packages).


## How to dive in?

- Report an issue
- Give me a Pull Request

## Who is Maintainer

- ChangJoo Park(pcjpcj2@gmail.com)
