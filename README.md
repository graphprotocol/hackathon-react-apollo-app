# Hackathon React Apollo Example

This is an example UI app for the hackathon. It uses [React](https://reactjs.org/), [Apollo](https://www.apollographql.com/docs/react/) and [MaterialUI](https://material-ui.com/) libraries.

## Contents

- This project is set up using `react-scripts`
- We use [Prisma](https://www.prisma.io/) to mock a GraphQL server. Connection to the Prisma endpoint is achieved though Apollo Client in [`src/apollo.js`](src/apollo.js).
- Example components can be found in [`src/components/`](src/components/)
- An example GraphQL schema can be found in [`src/domain/schema.graphql`](src/domain/schema.graphql)

## Build and run

1.  Run `yarn` to install dependencies.
2.  Run `yarn start` to serve the example components on http://localhost:3000
3.  Run `yarn build` to build the code for production

## License

Copyright © 2018 Graph Protocol, Inc.

Licensed under the [MIT License](LICENSE).
