<h1><img src="'./logo/conflux-logo.png" alt="Conflux library logo" height="60" aria-lable="Conflux library logo" /></h1>

Conflux is a modularized state management system utilizing the [Context API](https://reactjs.org/docs/context.html) and [React Hooks](https://reactjs.org/docs/hooks-intro.html) for the [React](https://reactjs.org/) ecosystem. It provides a predictable state container for applications in an elegant, streamlined, and developer-friendly manner.

## Table of Contents

- [Why Use Conflux?](#why-use-conflux)
- [Learn Conflux](#learn-conflux)
- [Developer Experience](#developer-experience)
- [Installation](#installation)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Why Use Conflux?

While `Context` and `Hooks` are relatively cutting-edge at the moment, the concept of global state management is familiar to even the newest of developers. Most existing systems currently revolve around a single global store. While this pattern does come with huge benefits, modern applications are so large and complex that these stores can sometimes give you "the forest with the tree" when one only needs partial slices of state.

Additionally, while most people use `Context` in React to pass global state up-and-down the entire application, it also has the ability to be surgically scoped to a specific tree within an application's component architecture. As most large chunks of state are sometimes only needed inside of their assigned section of the application, modularity, maintainability, and performance can all be improved by segmenting state to specific limbs of the component tree.

## Learn Conflux

## Developer Experience

## Installation

## License

MIT

## Acknowledgements

- [Redux](https://github.com/reduxjs/redux) - A phenomenal application of state management that paved the way for some of the patterns used in this library
