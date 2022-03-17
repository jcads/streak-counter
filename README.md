# `@jcads/streak-counter` - a basic streak counter

This is a basic streak counter for the browser, inspired by Duolingo - written in Typescript and meant for the browser (uses `localstorage`)

## Install

yarn add @jcads/streak-counter

npm install @jcads/streak-counter

## Usage

```javascript
import { streakCounter } from "@jcads/streak-counter";

const today = new Date();
const streak = streakCounter(localStorage, today);
// streak returns an object:
// {
//    currentCount: 1,
//    lastLoginDate: "11/11/2021",
//    startDate: "11/11/2021",
// }
```
