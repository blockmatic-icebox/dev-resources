# The Pura Vida React Stack

A collection of guidelines, tools, talks and packages for React applications.

_TLDR: Hooks, Functional JavaScript, TypeScript, Emotion, Pose, Fluid Layout and Typography._

## Must Know / Watch

- video: [Everything You Know About Web Design Just Changed](https://www.youtube.com/watch?v=jBwBACbRuGY)
- video: [Must know JavaScript features](https://www.youtube.com/watch?v=W4brAobC2Hc&list=PL0zVEGEvSaeHJppaRLrqjeTPnCH6vw-sm) 
- video: [Declarative programming](https://www.youtube.com/watch?v=yGh0bjzj4IQ) 
- video: [What the heck is the event loop anyway?](https://www.youtube.com/watch?v=8aGhZQkoFbQ) 
- video: [In the loop](https://www.youtube.com/watch?v=cCOL7MC4Pl0) 
- video: [How does the browser actually render a website](https://www.youtube.com/watch?v=SmE4OwHztCc) 
- video: [Composition over Inheritance](https://www.youtube.com/watch?v=wfMtDGfHWpA)

## Layout & CSS

- video: [Designing for A Viewport](https://www.youtube.com/watch?v=QY3lTBZnJmE)
- video: [Introduction to Viewport Units](https://www.youtube.com/watch?v=_sgF8I-Q1Gs)
- video: [Basics of CSS Grid: The Big Picture](https://www.youtube.com/watch?v=FEnRpy9Xfes)
- video: [Flexbox CSS In 20 Minutes](https://www.youtube.com/watch?v=JJSoEo8JSnc)
- video: [Flexbox vs. CSS Grid?](https://www.youtube.com/watch?v=hs3piaN4b5I)
- video: [Using Flexbox + CSS Grid Together](https://www.youtube.com/watch?v=dQHtT47eH0M)
- collection: [All The Videos in Layout Land](https://www.youtube.com/watch?v=FEnRpy9Xfes&list=PLbSquHt1VCf18lllS0C5quAaOcsuMAC70&index=1)
- article: [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- article: [A Complete Guide to Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

## Typography

- video: [Advanced Fluid Typography (and more) by Mike Riethmuller](https://www.youtube.com/watch?v=mAvQUIKtW_Y)
- article: [Fluid Typography With vh And vw Units](https://www.smashingmagazine.com/2016/05/fluid-typography/)
- article: [More Meaningful Typography](http://alistapart.com/article/more-meaningful-typography/)
- tool: [Type Scale](https://type-scale.com/)
- tool: [Modular Scale](https://www.modularscale.com)
- video: [Simple Explanation Of rem & em CSS Units](https://www.youtube.com/watch?v=H4UtKu11yXg)

## Functional JavaScript with TypeScript 

- video: [Functional Programming in JavaScript](https://www.youtube.com/watch?v=BMUiFMZr7vk&list=PL0zVEGEvSaeEd9hlmCXrk5yUyqUag-n84)
- article: [JSX in TypeScript](https://www.typescriptlang.org/docs/handbook/jsx.html)

## React Hooks and Context 

- video: [React Today and Tomorrow and 90% Cleaner React With Hooks](https://www.youtube.com/watch?v=dpw9EHDh2bM) 
- video: [Let's hook up with React](https://www.youtube.com/watch?v=h9qHKDlsnP0) 
- video: [Fun with React Hooks](https://www.youtube.com/watch?v=1jWS7cCuUXw)
- video: [React Hooks Make Using Context 10x Better](https://www.youtube.com/watch?v=cBM5xXyekmM)

## Animation

- video: [Dead simple animation with React Pose](https://www.youtube.com/watch?v=BSbVB14riQI)
- video: [Snap.SVG Animator](https://www.youtube.com/watch?v=waTuhjBSJrs)
- github: [React CSS Transition Replace](https://github.com/marnusw/react-css-transition-replace)
- github: [React Transition Group](https://github.com/reactjs/react-transition-group/)
- article: [Canvas vs. SVG: Choosing the Right Tool for the Job](https://www.sitepoint.com/canvas-vs-svg-choosing-the-right-tool-for-the-job/)
- github: [React GSAP (GreenSock Animation Platform)](https://github.com/bitworking/react-gsap)
- video: [Declarative future of gestures and animations in React Native](https://www.youtube.com/watch?v=kdq4z2708VM)
- github: [Lottie animation view for react ](https://github.com/chenqingspring/react-lottie)
- github: [React Flip Toolkit](https://github.com/aholachek/react-flip-toolkit)

## Styling

- website: [Emotion library](https://emotion.sh/docs/introduction)
- video: [Artistic CSS](https://www.youtube.com/watch?v=aQBYAkaABkU)

## Code Conventions

### Components as function & methods as arrow functions

```jsx
function MyContainer () { 
 const myMethod = () => { }  
    
 return <b/>;
}
```

### Keep things that don't change outside of React components in VanillaJS

Ej. defaults, constants, browser configuration.

```jsx
const userAgent:string|undefined = window.navigator.userAgent;
const pageTitle:string = randomTitle();

function MyContainer () {
 return <b/>;
}
```

### Use type inference for defining component state or default props

```

```

### Don't use enum

```

```

### Variable and function names in camelCase, tolerate snakeCase attributes ( eosio cpp style )

```

```


## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
<table>
  <tr>
    <td align="center"><a href="https://gaboesquivel.com"><img src="https://avatars0.githubusercontent.com/u/391270?v=4" width="100px;" alt="Gabo Esquivel"/><br /><sub><b>Gabo Esquivel</b></sub></a><br /><a href="#ideas-gaboesquivel" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="https://kevinwolf.me"><img src="https://avatars2.githubusercontent.com/u/3157426?v=4" width="100px;" alt="Kevin Wolf"/><br /><sub><b>Kevin Wolf</b></sub></a><br /><a href="#ideas-kevinwolfcr" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="https://github.com/laubits"><img src="https://avatars3.githubusercontent.com/u/11317931?v=4" width="100px;" alt="Laura Castillo"/><br /><sub><b>Laura Castillo</b></sub></a><br /><a href="#ideas-laubits" title="Ideas, Planning, & Feedback">🤔</a></td>
    <td align="center"><a href="https://github.com/veyyz"><img src="https://avatars1.githubusercontent.com/u/4465736?v=4" width="100px;" alt="veyyz"/><br /><sub><b>veyyz</b></sub></a><br /><a href="#ideas-veyyz" title="Ideas, Planning, & Feedback">🤔</a></td>
  </tr>
</table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
