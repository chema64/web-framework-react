# JCU Web Framework for React

This package can be used in two different ways: as a library of React
components or as the Living Style Guide for James Cook University.

## Requirements

* Node 8.9.1 LTS (or above) and Yarn
* Static web hosting (such as <https://research.jcu.edu.au>)
* Access to JCU Web Framework via CDN

## Development

To set up for development, run the following:

    yarn
    yarn start

To run the tests on the code:

    yarn test

You can also check code coverage using:

    yarn test --coverage

You can debug interactively using Chrome's Developer Tools or Node's CLI
inteface using the commands respectively:

    yarn test-inspect
    yarn test-inspect-cli

## Deployment

    yarn && yarn build

Now, copy files located within `styleguide/` to your static web host.
