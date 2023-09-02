<h1 align="center">React template</h1>
<br/>

<div align="center">
    <img src='./images/home.png' style='width: 75%'/>
</div>
<br>
<p align="center">
    <a href="../README.md">简体中文</a> |  English
</p>

## 🔗 Demo

-   preview (PC) [react-enterprise-template](https://kothing.github.io/react-enterprise-template/)
-   preview（mobile） [react-template-mobile](https://github.com/kothing/react-template-mobile)

## 👨🏻‍💻 Project Description

-   mobile template: [react-template-mobile](https://github.com/kothing/react-template-mobile)

-   React template, a more rich template than CRA.

-   Development configuration documentation [React18 + webpack5 + TypeScript4 + react-router-dom](https://juejin.cn/post/7197790401495121977)

-   Project Creation Tutorial [<Building a React Project Development Template from 0 to 1>](https://juejin.cn/post/7223267430231326778)

## 📱 Features

-   📦 Out of the box, no configuration required.
-   📝 Comprehensive comment explanations, low learning cost.
-   🚀 Fast startup and compilation.
-   🌱 Highly customizable, easy to expand.

## 🚀 Technology Stack

[![react](https://img.shields.io/badge/react-18.2.0-brightgreen.svg)](https://github.com/facebook/react/) [![TypeScript](https://img.shields.io/badge/TypeScript-4.9.4-brightgreen.svg)](https://github.com/microsoft/TypeScript)[![webpack](https://img.shields.io/badge/webpack-5.75.0-brightgreen.svg)](https://github.com/facebook/react/) [![axios](https://img.shields.io/badge/axios-0.18.0-brightgreen.svg)](https://github.com/axios/axios) [![mobx](https://img.shields.io/badge/mobx-6.8.0-brightgreen.svg)](https://github.com/mobx) [![react-router-dom](https://img.shields.io/badge/react--router--dom-6.8.1-brightgreen.svg)](https://github.com/remix-run/react-router) [![MIT](https://img.shields.io/badge/license-MIT-brightgreen.svg)]()

-   React v18
-   react-dom v18
-   React Hook
-   TypeScript v4
-   webpack v5
-   axios v1
-   mobx v6
-   mobx-react-lite v3
-   react-router-dom v6

## 🎄 Upcoming Features:

-   ① A ✅
-   ② B ✅
-   ③ C ✅
-   ④ D ✅ ✨
-   ⑤ E ✅ ✨
-   ⑥ F ✅ ✨
-   ⑦ G ✅ ✨
-   ⑧ H ✅ ✨
-   ⑨ I ✅ ✨
-   ⑩ J ✅ ✨
-   ⑪ K ✅ 📝

## ⌛️ Install project dependencies

-   `npm` >= 6.14.x
-   `node` >= 16.30.x

```
npm
$ npm install

yarn
$ yarn
```

## 🚀 Run the project

```
npm
$ npm run start

yarn
$ yarn dev
```

## 📦 Packaging and compilation

```
npm run build:qa  // Testing environment
npm run build:prod  // Production environment
```

## 🏷 Branch description

| Branch | description        |
| ------ | ------------------ |
| main   | Main branch        |
| deploy | demo deploy        |
| dev    | Development branch |

## Code submission specification

```
git <type>: <subject>
git commit -m "feat: Project initialization"
```

### type 参考:

```
fix       🐛 Bug fix
feature   ✨ Introduce new features
docs      📝 Document writing changes
prune     🔥 Remove code or files
ui        💄 Update UI and style files
perf      ⚡ Performance-related optimizations
rocket    🚀 Deployment function
style     🎨 Style modification
init      🎉 Initial submission
release   🔖 Release version
wip       🚧 Work in progress, and unstable submissions may occur
config    🔧 Modify configuration file
refactot  🔨 Refactoring (code changes that neither add new features nor fix bugs)
merge     🔀 Merge branches
```

## 📂 Directory Structure

```
    ├── .vscode
    │   └──setting.json                 # Configuration for vscode that takes precedence over global settings.json
    ├── doc                             # Development documentation
    ├── webpack                         # Packaging and compilation
    │   └──config                       # Webpack configuration
    │       ├── webpack.common.js       # Base configuration
    │       ├── webpack.dev.js          # Development environment configuration
    │       └──webpack.prod.js          # Production environment configuration
    ├── pubilc
    │   ├──favicon.ico                  # HTML icon
    │   └──index.html                   # HTML entry template
    ├── src
    |   ├── api                         # Interface configuration
    |   ├── assets                      # Static resources
    │   ├── components                  # Common components of the project
    │   ├── http                        # Unified encapsulation of requests
    │   ├── httpinterface               # TypeScript type definition
    │   ├── constData                   # Constant list within the system
    │   ├── router                      # Unified routing entry
    │   ├── store                       # Data sharing
    │   ├── styles                      # Global style
    │   ├── utils                       # Utility library
    │   ├── view                        # Pages
    │   ├── App.tsx                     # Main interface
    │   └──index.tsx                    # Entry file
    ├── .babelrc.js                     # Babel configuration
    ├── .editorconfig                   # Maintaining consistent coding style across editors
    ├── .env.json                       # Environment variable configuration
    ├── .eslintignore                   # Files ignored by ESLint
    ├── .eslintrc.js                    # ESLint configuration
    ├── .gitignore                      # Files ignored by git submission
    ├── .npmrc
    ├── .prettierignore                 # Files ignored by prettierc
    ├── .prettierrc                     # Prettierc configuration
    ├── .stylelintrc.js                 # Code style configuration
    ├── LICENSE                         # Open source license
    ├── package-lock.json               # npm package lock management
    ├── package.json                    # Dependency management
    ├── README.md                       # Project description
    ├── tsconfig.json                   # TypeScript configuration file
    └── yarn.lock                       # Yarn package lock management


```

## 📚 Development reference

-   <a href="./data.md">Development reference</a>

## 🤝 How to Contribute

-   📬 If you have any questions, please open an issue or leave a message
-   🧙‍♀️ Welcome all contributors, come to Issus or submit Pull Requests to become a contributor

## ⭐️ Stargazers

[![Stargazers](Stargazers)](https://github.com/kothing/react-enterprise-template/stargazers)

## 💡 Open Source License

The code and documentation of this project are released under the MIT License open source license.
