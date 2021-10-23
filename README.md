# react-looping-typewriter

## Installation

```shell
npm install react-looping-typewriter
```

## Usage

Pass in the text you want to type the `textToType` prop to the `<Typewriter />` component.

```jsx
import React from 'react';
import Typewriter from 'react-looping-typewriter';

const App = () => {
  return <Typewriter textToType='Hello World!' />;
};
```

## Documentation

### Typewriter

#### props.wpm

type: `Integer` default: `100`

Typing speed in words per minute of the component

#### props.loop

type: `Boolean` default: `false`

Looping behavior of the component. When set to `true` the typewriter will pause, 'delete' the text, and repeat.

#### props.pause

type: `Integer` default: `1`

If `props.loop === true`: time in seconds the typewriter will pause before looping.
