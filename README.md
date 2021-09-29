# Vuetify Sign in/ Sign up
This project is based on an ["AAE IdeaPro" Vuetify tutorial](https://www.youtube.com/watch?v=XPOyEUpMGPQ).

## Project Overview

This is a sign in/sign up page made out of Vuetify components. This is just a shell, without any real functionality. In addition, all code is in one single page - no components. Checkout other branchs to see the evolution of this project.

### Main Screen

<img src="./pics/MainPage.gif" />

The main page consists of two main `window` elements. The `window` component controls the transitions.

## Branch Features

This branch breaks down the original structure into two individual components: `Signin` and `Signup`. In a nutshell, each `v-window-item` became a component. This change, demanded using events. This can be further improved by using slots. Checkout commits to see the changes.

## Project setup
```
yarn install
```

```
yarn serve
```
