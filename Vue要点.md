### `<template>`妙用
- 可以用来包裹if块

  ```
  <template v-if="seen">
  
    <p>Can U see me?</p>
    <span>HAHAHA</span>
    
  </template>
  ```
  > 只能用来包裹`v-if`，不能用来包裹`v-show`
- 包裹列表渲染块
  
  ```
  <ul>
    <template v-for="item in items">
      <li>{{ item.msg }}</li>
      <li class="divider"></li>
    </template>
  </ul>
  ```
