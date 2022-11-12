# Chakra UI

## What is a Chakra UI?

Chakra UI is a component-based library. It's made up of basic building blocks that can help you build the front-end of your web application.

It is customizable and reusable, and most importantly it supports ReactJs, along with some other libraries too.


## Is Chakra UI better than material UI?

|  different | Chakra UI |  Material UI |
| ----------- | ----------- | -----------|
| flexibility | The Chakra UI has a much cleaner classNames structure   |  Material UI adds numerous classes to each HTML tag created for material components|
| ease of use | slightly quicker and easier than Material UI  | easy to used|
|performance| Material UI is the winner when it comes to performance for your website|Chakra UI has sufficient performance for small- to medium-sized websites|

# How to use Chakra UI?

for install Chakra UI  run this command  in your termina if tou used npm to install package

```js
npm i @chakra-ui/react @emotion/react @emotion/styled framer-motion
```
After installing Chakra UI, you need to set up the ChakraProvider at the root of your application.
This can be either in your index.jsx, index.tsx or App.jsx depending on the framework you use.

```js
import * as React from 'react'

// 1. import `ChakraProvider` component
import { ChakraProvider } from '@chakra-ui/react'

function App() {
  // 2. Wrap ChakraProvider at the root of your app
  return (
    <ChakraProvider>
      <TheRestOfYourApplication />
    </ChakraProvider>
  )
}
```
thwn start style for using Chakra UI click here for [Chakra UI doc](https://chakra-ui.com/getting-started)

