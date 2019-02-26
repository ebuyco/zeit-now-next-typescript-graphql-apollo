This example combines:

- [Yarn Workspaces](https://yarnpkg.com/lang/en/docs/workspaces/)
- [React Apollo](https://github.com/apollographql/react-apollo)
- [Apollo Server](https://github.com/apollographql/apollo-server)
- [Apollo Codegen](https://github.com/apollographql/apollo-tooling)
- [Next.js](https://github.com/zeit/next.js/)
- [Now 2.0](https://github.com/zeit/now-cli)
- [Typescript](https://github.com/Microsoft/TypeScript) 

to build a Monorepo FullStack GraphQL App which can be deployed by a single command `now`.

## Direct ancestors

- [HelloWorld in TypeScript](https://github.com/softspider/typescript)
- [Minimalistic Next.js example](https://github.com/softspider/next.js)

## Direct descendants

Yet absent

---

## Install

`yarn`

## Running(dev)

`cd api && yarn dev`

`cd www && yarn dev`

## Generate Types

With api running

`cd www && yarn gen`

## Deploy

`now`


## Inspired by

[An Apollo Server & Client in a yarn Workspace deployed with Zeit 2.0](https://github.com/DennisKo/zeit-now-next-apollo-typescript-example)

### License

Licensed under the [MIT license](./LICENSE).
