vscode environment for jest

## Installation

```
npm install jest-environment-vscode
```

or

```
yarn add jest-environment-vscode
```

## Usage

By adding the "vscode" as testEnvironment in your jest config, for example in the package.json

```json
"jest": {
  "roots": [
    "<rootDir>/test/jest"
  ],
  "verbose": true,
  "silent": true,
  "testEnvironment": "vscode"
}
```
