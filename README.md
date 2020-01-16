# example-circleci-node-ecr

This is an example repo that uses [FeaturePeek](https://featurepeek.com) to spin up collaborative feature environments for every pull request. 

This particular repo uses:

- the [CircleCI](https://travis-ci.com) continuous integration service
- the [Express](https://expressjs.com) server for [Node.js](https://nodejs.org)
- the [Amazon Elastic Container Registry (ECR)](https://aws.amazon.com/ecr/) container registry

## Files of note

- [`/peek.yml`](https://github.com/featurepeek/example-circleci-node-ecr/blob/master/peek.yml): FeaturePeek config file
- [`/.circleci/config.yml`](https://github.com/featurepeek/example-circleci-node-ecr/blob/master/.circleci/config.yml): Continuous Integration config file


## More examples

Check out [more FeaturePeek example repos](https://github.com/featurepeek?utf8=✓&q=example&type=&language=) to find out how to integrate with FeaturePeek using different combinations of CI services, front-end frameworks, and container registries. 
