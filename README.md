# DITO UIkit

[![Version](https://img.shields.io/npm/v/dito-uikit)](https://www.npmjs.com/package/dito-uikit) [![Size](https://img.shields.io/bundlephobia/min/dito-uikit)](https://www.npmjs.com/package/dito-uikit)

DITO UIkit is a set of React components and hooks used to build pages on DITO's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add dito-uikit`

## Setup

### Theme

Before using Pancake UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from 'dito-uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from 'dito-uikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.
