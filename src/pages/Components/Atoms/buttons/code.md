---
title: 'SCSS - Base'
order: 2
---

## Available style

### Solid

To create a solid button you have one main class to apply `ga-button`. 
```html
    <a href="#" class="ga-button"></a>
```
<pattern path="src/patterns/--button/intro"></pattern>

### Bordered 

To create a default bordered button you will need to add a second class `ga-button--bordered`;
```html
    <a href="#" class="ga-button ga-button--bordered"></a>
```
<pattern path="src/patterns/--button/intro-bordered"></pattern>


## Available sizes

You can use one of the 3 available sizes :
* **small** : `--small`
* **medium** : this is the default style so you don't need to add a modifier class
* **large** : `--large`;

```html
    <a href="#" class="ga-button ga-button--small">Button</a>
    <a href="#" class="ga-button ga-button--large">Button</a>
```

<pattern path="src/patterns/--button/button-sizes"></pattern>

### Responsive classes

| Default | `ga-button--small` | `ga-button--medium` | `ga-button--large` |
| ---------- | - | - |
| From breakpoint m | `ga-button--small@from-m` | `ga-button--medium@from-m` | `ga-button--large@from-m` |
| From breakpoint l | `ga-button--small@from-l` | `ga-button--medium@from-l` | `ga-button--large@from-l` |
| From breakpoint xl | `ga-button--small@from-xl` | `ga-button--medium@from-xl` | `ga-button--large@from-xl` |
| From breakpoint xxl | `ga-button--small@from-xxl` | `ga-button--medium@from-xxl` | `ga-button--large@from-xxl` |

## Available color themes

| Solid | Bordered |
| ----- | -------- |
| <ul><li>`solid`</li><li>`solid-secondary`</li><li>`solid-primary-campus`</li><li>`solid-danger`</li></ul> | <ul><li>`bordered`</li><li>`bordered-secondary`</li><li>`bordered-primary-campus`</li><li>`bordered-danger`</li></ul> |


```html
    <a href="#" class="ga-button ga-button--primary-campus" >Button</a>
    <a href="#" class="ga-button ga-button--bordered-primary-campus" >Button</a>
```

<pattern path="src/patterns/--button/button-styles"></pattern>

## States

Classics states are available :
* `hover`
* `active`
* `focus`
* `disabled`

<pattern path="src/patterns/--button/button-state"></pattern>

## Available display

To manage display of your button, you have 2 availables classes :
* `ga-button--fit` : Applied by default
* `ga-button--full`

```html
    <a href='#' class="ga-button ga-button--full">My button</a>
```

### Responsive classes

| Default | `ga-button--full` | `ga-button--fit` |
| ---------- | - | - |
| From breakpoint m | `ga-button--full@from-m` | `ga-button--fit@from-m` |
| From breakpoint l | `ga-button--full@from-l` | `ga-button--fit@from-l` |
| From breakpoint xl | `ga-button--full@from-xl` | `ga-button--fit@from-xl` |
| From breakpoint xxl | `ga-button--full@from-xxl` | `ga-button--fit@from-xxl` |