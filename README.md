# How-to-safely-split-BCH-and-BCHA-coins-BitcoinCash-BitcoinABC-Hard-Fork-2020
This upgrade is expected to fork Bitcoin Cash out of two chains, BCHA (Bitcoin Cash ABC) and BCH (Bitcoin Cash Node)

The goal of Bitcoin Cash Node is to create sound money that is usable by everyone in the world. We believe this is a civilization-changing technology which will dramatically increase human flourishing, freedom, and prosperity. The project aims to achieve this goal by implementing a series of optimizations and protocol upgrades that will enable peer-to-peer digital cash to scale many orders of magnitude beyond current limits.

## What is Bitcoin Cash?
Bitcoin Cash is a digital currency that enables instant payments to anyone, anywhere in the world. It uses peer-to-peer technology to operate with no central authority: managing transactions and issuing money are carried out collectively by the network. Bitcoin Cash is a descendant of Bitcoin. It became a separate currency from the version supported by Bitcoin Core when the two split on August 1, 2017. Bitcoin Cash and the Bitcoin Core version of Bitcoin share the same transaction history up until the split.

## What is Bitcoin Cash Node?
[Bitcoin Cash Node](bitcoincashnodes.org) is the name of open-source software which enables the use of Bitcoin Cash. It is a descendant of the Bitcoin Core and Bitcoin ABC software projects.

## License
Bitcoin Cash Node is released under the terms of the MIT license. See COPYING for more information or see https://opensource.org/licenses/MIT.

## Run the develoment server
You will need [nodeJS](https://nodejs.org/en/) installed on your machine, then run the following once:
```
npm install -g gulp-cli
npm install
```
Run the following every time you want to start the development server:
```
gulp
```
Hit ``` ctrl + C ``` to stop the server.

## Writing an article
In ```/blog/```, copy the ```example.md``` file and replace the content. Run ```gulp``` to preview the article in the browser (located at http://localhost:3000/en/newsroom/filename).

## Translating
Translations are managed through [Crowdin](https://crowdin.com/). If you wish to translate this website into your own language, please open an issue at this repo.

Pull requests are automatically created when a translation is updated.

[<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg' alt='github' height='40'>](https://github.com/BitcoinCashNodes)  
