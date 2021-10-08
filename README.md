## Battle-tested React Native boilerplate

The culmination of five years of constant React Native development, Ignite is the most popular React Native app boilerplate for both Expo and bare React Native.

## Tech Stack

Ignite apps include the following rock-solid technical decisions out of the box:

- React Native
- React Navigation 6
- MobX-State-Tree [(Why not Redux?)](https://github.com/infinitered/ignite/blob/master/docs/MobX-State-Tree.md)
- MobX-React-Lite
- TypeScript
- MMKV Storage (integrated with MST for restoring state)
- apisauce (to talk to REST servers)
- Flipper-ready
- Reactotron-ready (and pre-integrated with MST)
- Supports Expo (and Expo web) out of the box
- And more!

## Quick Start

Run the CLI:

```bash
# for vanilla React Native
npx ignite-cli new PizzaApp
# or for Expo-powered:
npx ignite-cli new PizzaApp --expo
# to provide a custom bundle identifier (Android only):
npx ignite-cli new PizzaApp --bundle=com.infinitered.pizzaapp
```

Ignite will walk you through the rest.

If you'd like to follow a tutorial, check out [this one from Robin Heinze](https://shift.infinite.red/creating-a-trivia-app-with-ignite-bowser-part-1-1987cc6e93a1).

### Troubleshooting

The above commands may fail with various errors, depending on your operating system and dependency versions. Some troubleshooting steps to follow:

- Make sure you are using the LTS version of Node. This can be checked via the `node --version` command. If you require multiple Node versions on your system, install `nvm`, and then run `nvm install --lts`. At the time of writing, Node LTS is v14.x.x.
- If the installation fails because of an XCode error (missing XCode command line tools), the easiest way to install them is to run `sudo xcode-select --install` in your terminal.
- If XCode and command line tools are already installed, but the installation complains about missing patch dependencies, you may need to switch the XCode location to something else: `sudo xcode-select -s /Applications/Xcode.app/Contents/Developer`

## Generators

_The hidden gem of Ignite._ Generators help you scaffold your app very quickly, be it for a proof-of-concept, a demo, or a production app. Generators are there to save you time, keep your code consistent, and help you with the basic structure of your app.

```
npx ignite-cli generate --help
```

...will give you information on what generators are present. To learn more, check out our [Generators](https://github.com/infinitered/ignite/blob/master/docs/Generators.md) documentation.

## Troubleshooting

If you run into problems, first search the issues in this repository. If you don't find anything, you can come talk to our friendly and active developers in the Infinite Red Community Slack ([community.infinite.red](http://community.infinite.red)).

## Further Reading

- Watch Jamon Holmgren's talk at React Live Amsterdam where he uses Ignite to build an app in less than 30 minutes: [https://www.youtube.com/watch?v=Pb8MWkQ9GOc](https://www.youtube.com/watch?v=Pb8MWkQ9GOc)
- Prior art includes [Ignite Andross](https://github.com/infinitered/ignite-andross) and [Ignite Bowser](https://github.com/infinitered/ignite-bowser) (which is very similar to the current version of Ignite).
- [Check out Gluegun](https://github.com/infinitered/gluegun) - Ignite CLI is powered by Gluegun, which lets you build CLI apps painlessly!
- [Who are We?](https://infinite.red) - Learn More About Infinite Red
