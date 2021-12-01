# GoldBonus UIkit

[![Version](https://img.shields.io/npm/v/gdb-uikit)](https://www.npmjs.com/package/gdb-uikit) [![Size](https://img.shields.io/bundlephobia/min/gdb-uikit)](https://www.npmjs.com/package/gdb-uikit)

GoldBonus UIkit is a set of React components and hooks used to build pages on GoldBonus's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add gdb-uikit`

## Setup

### Theme

Before using Pancake UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from 'gdb-uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from 'gdb-uikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.
