# CircleCI Image Docs [![CircleCI Build Status](https://circleci.com/gh/CircleCI-Public/cimg-docs.svg?style=shield&circle-token=4e5737d97ecf8b6e9cc1fa7151951792c9ca2fb7)](https://circleci.com/gh/CircleCI-Public/cimg-docs) [![GitHub License](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/CircleCI-Public/cimg-docs/master/LICENSE) [![CircleCI Community](https://img.shields.io/badge/community-CircleCI%20Discuss-343434.svg)](https://discuss.circleci.com)

This is the source repository for CircleCI Image Docs, a static website generated by [Hugo](https://GoHugo.io/).
Instructions for building the website locally are below, but a staging/testing version can be found [here](https://image-docs.circleci.io/).


## Run Locally

You can run this website locally by cloning this repo and serving it with Hugo.
If you don't already have Hugo installed, visit Hugo Docs and follow the [Hugo Install Instructions](https://gohugo.io/getting-started/installing/).

```
git clone git@github.com:CircleCI-Public/cimg-docs.git
cd cimg-docs
hugo -s src serve
```

You'll then be able to view the site in your browser at `http://localhost:1313/`.
