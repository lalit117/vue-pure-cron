# Vue Pure Cron

[![npm](https://img.shields.io/npm/v/vue-pure-cron.svg)](https://www.npmjs.com/package/vue-pure-cron)

## Introduction
Vue pure cron is a vue component designed to generate commonly used cron expression.

## Install via npm
```
npm install vue-pure-cron --save
```

## Quick Start
```
import Vue from 'vue';
import PureCron from 'vue-pure-cron';

Vue.use(PureCron);
```

## Attributes
| Attribute name |Description|Type|Default|Attention
|-|-|-|-|-|
|width|width of the component|string, number|`'100%'`|Component has a min-width of 420px|
|showOperationPanel|If operation panel is displayed|boolean|`true`|-|

## Events
| Event name|Description| Parameters|Attention
|-|-|-|-|
|generate|triggers when confirm btn is clicked|exp(generated cron expression)|confirm btn only shows when showOperationPanel attr is `true`|