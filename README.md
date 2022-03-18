# storybook-tutorial

# install nvm/node

- install nvm / node
  - [nvm github](https://github.com/nvm-sh/nvm)
  - `wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash`

```sh
export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm
```

- `nvm install lts/gallium` which the node version is v16.14.1
- `nvm alias default 'lts/gallium'`
- `npm install --global yarn`

# Tutorials

```sh
# Add Storybook:
npx sb init
```

https://storybook.js.org/tutorials/

# [Tutorial 1: Intro to Storybook](https://storybook.js.org/tutorials/intro-to-storybook/)

## [1. Get Started](https://storybook.js.org/tutorials/intro-to-storybook/react/en/get-started/)

```sh
npx degit chromaui/intro-storybook-react-template taskbox
cd taskbox
yarn

# Run the test runner (Jest) in a terminal:
yarn test --watchAll

# Start the component explorer on port 6006:
yarn storybook

# Run the frontend app proper on port 3000:
yarn start
```

## [2. Simple component](https://storybook.js.org/tutorials/intro-to-storybook/react/en/simple-component/)
