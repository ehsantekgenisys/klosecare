# Klosecare

---

## :arrow_up: Pre-requisites

- `Node.js` - Version 8 or newer
- `npm` - Node Package Manager (NPM)
- `react-native-cli` - Install [react-native-cli](https://github.com/react-native-community/cli) globally in your OS with one of the following commands.

```
npm install -g react-native-cli
or
yarn global add react-native-cli
```

- `jdk` - Java Development Kit (JDK 8 or newer)

Follow the [Getting Started](https://facebook.github.io/react-native/docs/getting-started.html) to setup the enviroments according to your OS .

## :arrow_up: Steps to run project (IOS)

1. Clone this repo using **ssh** or **https**

   - For ssh: `git@gitlab.com:emumba/klosecare/klosecare_mobile.git`
   - For https: `https://gitlab.com/emumba/klosecare/klosecare_mobile.git`

2. Move into the directory `klosecare_mobile`
3. Run `yarn install` or `npm install` to install the dependencies.
4. Install pods using `cd ios/ && pod install && cd ..`
5. Run project using `react-native run-ios`
