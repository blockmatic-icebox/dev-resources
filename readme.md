

# Modern React Stack

A curated collection of tutorials, talks, guidelines and tools for building performant React and React Native applications.   

__Functional JS, TypeScript, GraphQL, Remix, Zustand, Stitches, Framer, Fluid Layout with Grid and Flex.__

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**

- [Functional JavaScript and Web Fundamentals](#functional-javascript-and-web-fundamentals)
- [TypeScript](#typescript)
- [Remix Framework](#remix-framework)
- [State Management](#state-management)
- [Layout & CSS](#layout--css)
- [Stitches, Design System and CSS-in-JS](#stitches-design-system-and-css-in-js)
- [Typography and Iconography](#typography-and-iconography)
- [Debugging](#debugging)
- [Performance](#performance)
- [Animation](#animation)
- [GraphQL](#graphql)
- [Translations / Internationalization (i18n)](#translations--internationalization-i18n)
- [React Hooks and Context](#react-hooks-and-context)
- [React Native & Expo](#react-native--expo)
- [Ethereum EVM](#ethereum-evm)
- [Continuous Integration & Delivery](#continuous-integration--delivery)
- [React Native Accesibility](#react-native-accesibility)
- [Contributors ✨](#contributors-)
- [Blockmatic](#blockmatic)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Functional JavaScript and Web Fundamentals  

These are fundamental concepts and knowledge on how the browser and javascript work. You need learn this in order to be able to develop javascript applications in a professional way.

- 🎬  [How does the browser actually render a website](https://www.youtube.com/watch?v=SmE4OwHztCc) 
- 🎬  [Declarative programming](https://www.youtube.com/watch?v=yGh0bjzj4IQ) 
- 🎬  [Composition over Inheritance](https://www.youtube.com/watch?v=wfMtDGfHWpA)
- 📝 [AHA Programming: Avoid Hasty Abstractions](https://kentcdodds.com/blog/aha-programming)
- 🎬  [Playlist: Functional Programming in JavaScript](https://www.youtube.com/watch?v=BMUiFMZr7vk&list=PL0zVEGEvSaeEd9hlmCXrk5yUyqUag-n84)
- 🎬  [React Composition & Specialization](https://www.youtube.com/watch?v=VaXlL8nIhHw)
- 🎬  [What the heck is the event loop anyway?](https://www.youtube.com/watch?v=8aGhZQkoFbQ) 
- 📦 [Jargon from the functional programming world in simple terms! ](https://github.com/hemanth/functional-programming-jargon)

## TypeScript

TypeScript allows you to strongly type your javascript functions to catch errors a build time and develop with confidence.  The type errors are not going to get to production. The developer experience is greatly improved though VS Code intellisense. 

- 📝 [TypeScript for JavaScript Programmerst](https://www.typescriptlang.org/docs/handbook/typescript-in-5-minutes.html)
- 📝 [JSX in TypeScript](https://www.typescriptlang.org/docs/handbook/jsx.html)
- 📦 [React TypeScript Cheatsheet](https://github.com/typescript-cheatsheets/react-typescript-cheatsheet)
- 📦 [TypeFest TypeScript Collection](https://github.com/sindresorhus/type-fest)

## Remix Framework

Server side rendering rendering framework for building perfomant react application following web standards.

- 🖥 [Remix Technical Explanation](https://remix.run/docs/en/v1/pages/technical-explanation)
- 🖥 [Remix Conventions](https://remix.run/docs/en/v1/api/conventions)
- 🎬  [Remix Crash Course | Full Stack React](https://www.youtube.com/watch?v=d_BhzHVV4aQ)
- 🎬  [Build a Project Management App with Remix](https://www.youtube.com/watch?v=QpP3daA2na4)

## State Management

While most state in Remix apps is managed on the backend and cookies, you will find that some global state for layout, ui flags and other application configuration will be required too, Zustand is the best tool for the job. 

- 📦 [Zustand Store](https://github.com/pmndrs/zustand) 
- 📦 [Simple Zustand Devtools](https://github.com/beerose/simple-zustand-devtools)
- 🎬  [Code Review: Zustand (small & fast state-management for React)](https://www.youtube.com/watch?v=1-GqEwFlG-E)

## Layout & CSS

The web has evolved and the modern css apis make it a lot easier to but responsive and fluid layouts. There's no longer need for column based grid systems, flexbox and css grid provide with everything you need for layout.

- 🖥 [Introduction to CSS Layout](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Introduction)
- 🎬  [Everything You Know About Web Design Just Changed](https://www.youtube.com/watch?v=jBwBACbRuGY)
- 🎬  [Flexbox CSS In 20 Minutes](https://www.youtube.com/watch?v=JJSoEo8JSnc)
- 🎬  [Basics of CSS Grid: The Big Picture](https://www.youtube.com/watch?v=FEnRpy9Xfes)
- 🎬  [Flexbox vs. CSS Grid?](https://www.youtube.com/watch?v=hs3piaN4b5I)
- 🎬  [Using Flexbox + CSS Grid Together](https://www.youtube.com/watch?v=dQHtT47eH0M)
- 🎬  [CSS Grid Tutorial | Responsive Crash Course](https://www.youtube.com/watch?v=SPFDLHNm5KQ)
- 📝 [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- 📝 [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
- 🖥 [Flexbox.help Generator](https://flexbox.help/)
- 🖥 [CSS Grid Generator](https://cssgrid-generator.netlify.com/)
- 📦 [Awesome CSS Grid](https://github.com/valentinogagliardi/awesome-css-grid)
- 🎬  [Designing for A Viewport](https://www.youtube.com/watch?v=QY3lTBZnJmE)
- 🎬  [Introduction to Viewport Units](https://www.youtube.com/watch?v=_sgF8I-Q1Gs)
- 📝 [Fun with Viewport Units](https://css-tricks.com/fun-viewport-units/)
- 🎬  [Layout Land Channel](https://www.youtube.com/watch?v=FEnRpy9Xfes&list=PLbSquHt1VCf18lllS0C5quAaOcsuMAC70&index=1)
- 📝 [Beyond Media Queries](https://theweb.rocks/beyondmediaqueries/)
- 🖥 [Learn CSS Grid](https://learncssgrid.com/)

## Stitches, Design System and CSS-in-JS

Stitches is the best state-of-art css-in-js framework, in combination with Toolabs DSM it provides the performance and developer experience for design system driven development.

- 🎬  [What are Design Tokens](https://www.youtube.com/watch?v=wtTstdiBuUk)
- 🎬  [The Future of the Front-End – Stitches CSS-in-JS Demo](https://www.youtube.com/watch?v=Gw28VgyKGkw)
- 🎬  [Pedro Duarte - Modulz, Radix, Stitches](https://www.youtube.com/watch?v=3zn3Lyys9Zk)
- 🎬  [Let's Build a Design System: Spacing Methods](https://www.youtube.com/watch?v=aXokV5In7YA)
- 🎬  [Design System Naming Conventions - A Practical Guide](https://www.youtube.com/watch?v=w2LFfOtPsoc)
- 🎬  [Guillermo Rauch on Merging Design and Developement](https://www.youtube.com/watch?v=3hccXiXI0u8)
- 🖥  [Toolabs Design System Manager](https://toolabs.com/)
- 🖥  [Stitches - CSS-in-JS with near-zero runtime](https://stitches.dev/)

## Typography and Iconography

- 🎬  [Typography Basics Explained](https://www.youtube.com/watch?v=rF0zvSrF438)
- 🎬  [Advanced Fluid Typography (and more) by Mike Riethmuller](https://www.youtube.com/watch?v=mAvQUIKtW_Y)
- 📝 [Precise Control Over Responsive Typography](https://www.madebymike.com.au/writing/precise-control-responsive-typography/)
- 📝 [Fluid Typography With vh And vw Units](https://www.smashingmagazine.com/2016/05/fluid-typography/)
- 📝 [More Meaningful Typography](http://alistapart.com/article/more-meaningful-typography/)
- 🔧  [Type Scale](https://type-scale.com/)
- 🔧  [Modular Scale](https://www.modularscale.com)
- 🎬  [Simple Explanation of rem & em CSS Units](https://www.youtube.com/watch?v=H4UtKu11yXg)
- 📦 [React SVG Icons](https://github.com/react-icons/react-icons)

## Debugging

React and react native debugging tools.

- 📦 [Devtools Cheatsheet](https://github.com/jaredwilli/devtools-cheatsheet)
- 🔧 [React Dev Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi?hl=en)
- 🔧 [Pesticide Extension](https://chrome.google.com/webstore/detail/pesticide-for-chrome-with/neonnmencpneifkhlmhmfhfiklgjmloi)
- 🎬  [What's New with React Dev Tools 4](https://youtu.be/QFKZmBMgvus?t=468)
- 🖥 [React Devtools Interactive Tutorial](https://react-devtools-tutorial.now.sh/)
- 🖥 [Flipper](https://fbflipper.com/)
- 📦 [React Native Debugger](https://github.com/jhen0409/react-native-debugger)
- 📦 [Reactotron](https://github.com/infinitered/reactotron)

## Performance

Optimizing for quality of user experience is key to the long-term success of any site on the web.

- 🖥  [Web Vitals](https://web.dev/learn-web-vitals/)
- 🎬  [Optimize for Core Web Vitals](https://www.youtube.com/watch?v=AQqFZ5t8uNc)
- 🎬  [Web Performance Tips and Tricks from the Trenches](https://www.youtube.com/watch?v=YJGCZCaIZkQ)

## Animation

- 🎬  [Working with Framer Motion](https://www.youtube.com/watch?v=fY1pUeFqTsE)
- 🖥 [Framer Motion](https://www.framer.com/motion)
- 📦 [Framer Motion demos](https://github.com/chenglou/react-motion/wiki/Gallery-of-third-party-React-Motion-demos)
- 🎬  [Moti - Uuniversal animation package for React Native](https://www.youtube.com/watch?v=ynSfSf9w99M)
- 🎬  [Declarative future of gestures and animations in React Native](https://www.youtube.com/watch?v=kdq4z2708VM)
- 📝 [Canvas vs. SVG: Choosing the Right Tool for the Job](https://www.sitepoint.com/canvas-vs-svg-choosing-the-right-tool-for-the-job/)
- 📦 [Lottie animation view for react ](https://github.com/chenqingspring/react-lottie)
- 📦 [React Flip Toolkit](https://github.com/aholachek/react-flip-toolkit)

## GraphQL

- 📦 [React Apollo Hooks](https://www.apollographql.com/docs/react/api/react-apollo/)
- 📦 [GraphQL Hooks](https://github.com/nearform/graphql-hooks)

## Translations / Internationalization (i18n) 

- 📦 [React i18next](https://react.i18next.com)
- 📦 [Remix i18next](https://github.com/sergiodxa/remix-i18next)

## React Hooks and Context

- 🎬  [Requisite React: Learn how to use React Hooks, Suspense & JSX - Kent C. Dodds](https://www.youtube.com/watch?v=tO8qHlr6Wqg)
- 🎬  [Simplify React Apps with React Hooks](https://egghead.io/courses/simplify-react-apps-with-react-hooks)
- 🎬  [React.js Hooks Crash Course](https://www.youtube.com/watch?v=-MlNBTSg_Ww)
- 🎬  [React Hooks by Nicolas Marcora - August 2019 ](https://www.youtube.com/watch?v=ymMeu3foD_0)
- 🖥 [Hooks API Reference](https://reactjs.org/docs/hooks-reference.html)
- 📦 [Awesome React Hooks](https://github.com/rehooks/awesome-react-hooks)
- 🎬  [React Today and Tomorrow and 90% Cleaner React With Hooks](https://www.youtube.com/watch?v=dpw9EHDh2bM) 
- 🎧 [Realigning Your Model of React After Hooks - With Dan Abramov](https://kentcdodds.com/chats-with-kent-podcast/seasons/01/episodes/realigning-your-model-of-react-after-hooks-with-dan-abramov)
- 📝 [When to useMemo and useCallback - Kent C. Dodds](https://kentcdodds.com/blog/usememo-and-usecallback)
- 🎬  [React Hook Pitfalls - Kent C. Dodds - React Rally 2019](https://www.youtube.com/watch?v=VIRcX2X7EUk)
- 🎬  [How React Hooks Change The Way We Build Forms](https://www.youtube.com/watch?v=8yo44xN7-nQ)
- 🎬  [React Hooks Tutorial (Custom Hooks) | Form Validation made easy](https://www.youtube.com/watch?v=SXIfnNvYrZE)
- 📝 [The Iceberg of React Hooks - Sandro Dolidze](https://medium.com/@sdolidze/the-iceberg-of-react-hooks-af0b588f43fb)
- 📝 [React Hooks: Memoization - Sandro Dolidze](https://medium.com/@sdolidze/react-hooks-memoization-99a9a91c8853)
- 🎬  [React Context & Hooks Tutorial](https://www.youtube.com/watch?v=6RhOzQciVwI&list=PL4cUxeGkcC9hNokByJilPg5g9m2APUePI)
- 🎬  [Let's hook up with React](https://www.youtube.com/watch?v=h9qHKDlsnP0) 
- 🎬  [Fun with React Hooks - Michael Jackson and Ryan Florence](https://www.youtube.com/watch?v=1jWS7cCuUXw)
- 🎬  [useContext() + useReducer() = Magic?](https://www.youtube.com/watch?v=R_7XRX7nLsw)
- 🎬  [React Hooks useContext](https://www.youtube.com/watch?v=xWXxkFzgnFM)
-  📝  [React Hooks in TypeScript](https://fettblog.eu/typescript-react/hooks/)
-  📝  [TypeScript and React Hooks](https://medium.com/@jrwebdev/react-hooks-in-typescript-88fce7001d0d)
- 🎬  [The useReducer Hook - Dave Ceddia](https://www.youtube.com/watch?v=sYDFCuZHrqw)
- 🎬  [Why I Love useReducer](https://www.youtube.com/watch?v=o-nCM1857AQ)
- 🖥 [Thinking in React Hooks](https://wattenberger.com/blog/react-hooks)
- 🎬  [useCallback Hook and React.memo to minimize re-renders](https://www.youtube.com/watch?v=3Yyx9rqokN8)
- 📝 [When to useLayoutEffect Instead of useEffect - Dave Ceddia](https://daveceddia.com/useeffect-vs-uselayouteffect/)
- 🎬  [React Custom Hooks](https://www.youtube.com/watch?v=G3qVfQ5l-Cg)
- 🎬  [React Hooks: What will happen to the Container/Presenter Pattern?](https://www.youtube.com/watch?v=l6GTpKLWllQ)
- 📝 [React Hooks - A deeper dive featuring useContext and useReducer](https://testdriven.io/blog/react-hooks-advanced/)
- 📝 [The State Reducer Pattern](https://kentcdodds.com/blog/the-state-reducer-pattern)
- 🎬  [React Hooks useContext Tutorial (Storing a User)](https://www.youtube.com/watch?v=lhMKvyLRWo0)
- 🎬  [Explore the useMemo, useCallback, and useRef Hooks in React](https://www.youtube.com/watch?v=IivieWL_g4s)
- 📝 [State Management with React Hooks — No Redux or Context API](https://medium.com/javascript-in-plain-english/state-management-with-react-hooks-no-redux-or-context-api-8b3035ceecf8)

## React Native & Expo

- 🎬  [Getting Started With Expo and React Native](https://www.youtube.com/watch?v=xAjkuVuLLvo)
- 🎬  [React Native CLI vs Expo](https://www.youtube.com/watch?v=uHlAM4ICi1s)
- 🎬  [Expo CLI](https://www.youtube.com/watch?v=9rK5FdbOqpk)
- 🎬  [React Native CLI](https://www.youtube.com/watch?v=DYA6QMsq1fM)
- 🖥 [React Native Web](https://github.com/necolas/react-native-web)
- 🎬  [Chen Feldman - React Native - Under the Bridge | React Next 2019](https://www.youtube.com/watch?v=_IiDHmAPH28)
- 🎬  [Walkthrough: Expo CLI](https://www.youtube.com/watch?v=9rK5FdbOqpk)
- 🖥 [Awesome React Native](https://www.awesome-react-native.com)
- 📦 [React Native Fast Image](https://github.com/DylanVann/react-native-fast-image)
- 🎬  [Why React Native Gesture Handler & Reanimated](https://www.youtube.com/watch?v=aoENL4gF9rE)

## Ethereum EVM 

- 📦  [useDapp](https://github.com/EthWorks/useDApp)
- 📦 [wagmi hooks](https://github.com/tmm/wagmi)
- 🖥 [TheGraph](https://thegraph.com/)
- 🖥 [ether.js](https://docs.ethers.io/v5/single-page/)
- 📦 [TypeChain](https://github.com/dethcrypto/TypeChain)
- 📦 [Web3-React](https://github.com/NoahZinsmeister/web3-react)
- 📦 [Web3 modal](https://github.com/Web3Modal/web3modal)
## Continuous Integration & Delivery

- 🖥 [lighthouse ci](https://github.com/GoogleChrome/lighthouse-ci)
- 🖥 [nevercode](https://nevercode.io/)
- 🖥 [fastlane](https://fastlane.tools/)
- 🖥 [appcenter](https://appcenter.ms/)
- 🖥 [firebase](https://firebase.google.com/products/app-distribution/)

## React Native Accesibility

- 🎬  [Accessibility with React Native Apps in a Blind World](https://www.youtube.com/watch?v=TFKPJKAbvbk)
- 🖥 [Android's Overlay Attacks](https://labs.f-secure.com/blog/how-are-we-doing-with-androids-overlay-attacks-in-2020/) - Vulnerability
- 🖥 [Cloak and Dagger](https://cloak-and-dagger.org/) - Vulnerability

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
<table>
  <tr>
    <td align="center"><a href="https://gaboesquivel.com"><img src="https://avatars0.githubusercontent.com/u/391270?v=4" width="100px;" alt="Gabo Esquivel"/><br /><sub><b>Gabo Esquivel</b></sub></a><br /><a href="#ideas-gaboesquivel" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="https://kevinwolf.me"><img src="https://avatars2.githubusercontent.com/u/3157426?v=4" width="100px;" alt="Kevin Wolf"/><br /><sub><b>Kevin Wolf</b></sub></a><br /><a href="#ideas-kevinwolfcr" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="https://github.com/laubits"><img src="https://avatars3.githubusercontent.com/u/11317931?v=4" width="100px;" alt="Laura Castillo"/><br /><sub><b>Laura Castillo</b></sub></a><br /><a href="#ideas-laubits" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="http://kevinrodriguez.io/"><img src="https://avatars3.githubusercontent.com/u/6248571?v=4" width="100px;" alt="Kevin Rodríguez"/><br /><sub><b>Kevin Rodríguez</b></sub></a><br /><a href="#ideas-kevinrodriguez-io" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="https://github.com/guayom"><img src="https://avatars3.githubusercontent.com/u/3279037?v=4" width="100px;" alt="Guayo Mena"/><br /><sub><b>Guayo Mena</b></sub></a><br /><a href="#ideas-guayom" title="Ideas, Planning, & Feedback">🤔</a></td>
  </tr>
</table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

## Blockmatic

Blockmatic is building a robust ecosystem of people and tools for the development of blockchain applications.

[blockmatic.io](https://blockmatic.io)

<!-- Please don't remove this: Grab your social icons from https://github.com/carlsednaoui/gitsocial -->

<!-- display the social media buttons in your README -->

[![Blockmatic Twitter][1.1]][1]
[![Blockmatic Facebook][2.1]][2]
[![Blockmatic Github][3.1]][3]

<!-- links to social media icons -->
<!-- no need to change these -->

<!-- icons with padding -->

[1.1]: http://i.imgur.com/tXSoThF.png (twitter icon with padding)
[2.1]: http://i.imgur.com/P3YfQoD.png (facebook icon with padding)
[3.1]: http://i.imgur.com/0o48UoR.png (github icon with padding)

<!-- icons without padding -->

[1.2]: http://i.imgur.com/wWzX9uB.png (twitter icon without padding)
[2.2]: http://i.imgur.com/fep1WsG.png (facebook icon without padding)
[3.2]: http://i.imgur.com/9I6NRUm.png (github icon without padding)


<!-- links to your social media accounts -->
<!-- update these accordingly -->

[1]: http://www.twitter.com/blockmatic_io
[2]: http://fb.me/blockmatic.io
[3]: http://www.github.com/blockmatic

<!-- Please don't remove this: Grab your social icons from https://github.com/carlsednaoui/gitsocial -->
