# circle-monorepo

This repo shows an example of a monorepo setup via swissknife

Our circle config has 3 workflows
- the client workflow should be run if clients/* or shared/* is changed
- the server workflow should be run if server/* or shared/* is changed
- the operations workflow should be run if operations/* is changed

We use [swissknife](https://circleci.com/orbs/registry/orb/roopakv/swissknife) to easily manage triggering the right workflows.
