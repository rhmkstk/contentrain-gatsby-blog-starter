---
createdAt: 1649854540276
slug: "hello-world"
title: "Hello World (example)"
ID: "872b3e54-79e0-46ed-8675-48bbf27f0971"
categories: []
description: "Hello, world! This is a demo post for `gatsby-theme-blog`."
tags: []
date: "2022-04-13 12:00"
---
Hello, world! This is a demo post for `gatsby-theme-blog`.

Delete me, and get writing!

```js:title=gatsby-config.js
module.exports = {
  plugins: [
    "gatsby-theme-blog", // highlight-line
    "gatsby-theme-notes",
  ],
}
```

This is another paragraph after the code block.

## This is a secondary heading

```jsx
import React from "react"
import { ThemeProvider } from "theme-ui"
import theme from "./theme"

export default props => (
  <ThemeProvider theme={theme}>{props.children}</ThemeProvider>
)
```
