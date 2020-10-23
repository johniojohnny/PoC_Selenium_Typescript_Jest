# PoC_Selenium_Typescript_Jest
宿のテストサイトを Selenium &amp; Typescript &amp; Jest で Page Object Pattern で書いてみた.



install nvm
use latest node
install yarn
yarn init -y

yarn add --dev typescript
yarn add --dev jest
yarn add --dev ts-jest
yarn add --dev @types/jest

add this in package.json
  "scripts": {
    "test": "jest"
  }


yarn add --dev selenium-webdriver

yarn test で テストが実行される
