# Sphynx UIkit

[![Version](https://img.shields.io/npm/v/@sphynxswap/uikit)](https://www.npmjs.com/package/@sphynxswap/uikit) [![Size](https://img.shields.io/bundlephobia/min/@sphynxswap/uikit)](https://www.npmjs.com/package/@sphynxswap/uikit)

Sphynx UIkit is a set of React components and hooks used to build pages on Sphynx's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @sphynxswap/uikit`

## Setup

### Theme

Before using Sphynx UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@sphynxswap/uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@sphynxswap/uikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.
