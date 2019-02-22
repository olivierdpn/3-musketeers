# Cash transfer

![cash](https://source.unsplash.com/qsCGtoDHNoM/800x600)

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [👆 Introduction](#-Introduction)
- [🎯 How to use it ?](#-How-to-use-it-?)
- [📚 Libraries](#%E2%80%8D-just-tell-me-what-to-do)
    - [Chalk](#cash-rdd-and-cdd)
  - [Meow](#starwars-tdd)
  - [Got](#about-conf)
  - [Money](#about-money)
  - [Ora](#about-ora)
- [🏃‍Step by step](#%E2%80%8D-steps-to-do)
- [👷‍Construction of the project](#about-construction)
- [Licence](#licence)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## 👆 Introduction

This program is able to transfer 1$USD in EUR, GBP and JPY and use the rate at the exact time.

We use for this exchange rates API to get the good rate !

## 🎯 How to use it ?

#### First step - Libraries installation : 

**Install** all the dependancies of the package.json used for this project (chalk, conf, got, meow, money,ora). To do this, place your terminal in the good repository and use the command :

    > npm i

#### Second step - Run your code :

**Run** your code from your terminal using :

    > node bin/index.js

    #see your results

The result will be in your console !

## 📚 Libraries used

1. **Chalk :**

 [**Chalk**](https://www.npmjs.com/package/chalk) is used to change the policies of the text on the result of the console.

2. **Meow :**

[**Meow**](https://www.npmjs.com/package/meow) is a framework to use CLI object. With this library you can do beautiful objects.

3. **Got :**

[**Got**](https://www.npmjs.com/package/got) is used to do web request to ask the API online. By default, it's a get request, bu you can modify the parameter in the options.

4. **Money :**

[**Money**](https://www.npmjs.com/package/money) is a very useful : simple and tiny JavaScript library for realtime currency conversion and exchange rate calculation, from any currency, to any currency.

5. **Ora :**

[**Ora**](https://www.npmjs.com/package/ora) is a elaegant terminal spinner. Used in this projet to put the green arrows before the results !

## 🏃 Step by step 

The program asks an API to get the current rates of 1 USD in EUR, GPB and JPY. It uses promise to wait for the answer before displaying the information when found.

A loading function is also coded to wait for the answers.

## 👷‍Construction of the project

3 files : 
* **Index.js** : to run the project and itialize many parameters. Also call cash.js
* **Cash.js** : call the API to get the good rates. Functions are coded here, loading function as well, display the result.
* **Constants.js** : to call the API.

## Licence

[Uncopyrighted](http://zenhabits.net/uncopyright/)

