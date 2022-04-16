![CircleCI](https://img.shields.io/circleci/build/github/markormesher/dragonlabs-eslint-config)
![npm](https://img.shields.io/npm/v/@dragonlabs/eslint-config)

# @dragonlabs/eslint-config

My standard ESLint/Prettier config for TypeScript/React/SCSS projects. Published as its own package to reduce duplication between projects.

## Installation and Usage

Install with yarn:

    yarn add --dev @dragonlabs/eslint-config

And install dependencies:

    yarn add --dev install-peerdeps
    yarn install-peerdeps @dragonlabs/eslint-config --yarn --dev --only-peers

Add it to `.eslintrc.json`:

    {
        "extends": "@dragonlabs/eslint-config"
    }

## Why "dragonlabs"?

It was late and I needed a name. DragonLabs is a reference to an old project and was the first thing that came to mind.
