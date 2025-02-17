**⚠️ This guide has moved to the [consolidated 18F guides repository](https://github.com/18F/guides).**

# Methods

The 18F Methods were created to describe how 18F puts human-centered design into practice. While this was developed primarily as an internal resource, we hope it can help *everyone* adopt the methods of human-centered design. 

## Why methods?

In order to function well within cross-functional teams, designers and other contributors need to know a few things: which methods they might choose from, why one particular method makes more sense than another at any given moment, and, once they’ve picked a method, how to actually execute it. 18F Methods collects this essential information as a series of cards. In practice, we’ve found the Methods can provide folks with a gateway into our work and build internal alignment around a shared vocabulary.

### Specific to 18F, specific to the federal government

It’s important to note that the 18F Methods are designed to account for two things that may not otherwise concern a more generic collection of design methods. First, these methods directly reflect and support 18F’s human-centered work. (They are also continuously updated in a human-centered way — how meta!) Second, 18F Methods are designed to keep federal employees on the happy side of the law. This collection specifically includes helpful information which designers working in the federal government may need, such as privacy and the [Paperwork Reduction Act](pra.digital.gov).

## Getting started

### Reading the Methods online

You’re presently looking at the Methods’ GitHub (code) repository. Please [visit our homepage](https://methods.18f.gov) to read the Methods online.

### Printing the Methods
To print a copy of the Methods for offline use, visit the [Methods print page](https://methods.18f.gov/print/). You may need to select `file → print…` from your web browser.

### Contributing to the Methods
For more information on contributing to the Methods (or even making a suggestion), see [CONTRIBUTING.md](https://github.com/18F/methods/blob/staging/CONTRIBUTING.md). If you would like to suggest a new Method be added to the collection, please follow the instructions [here](https://github.com/18F/methods/wiki/Contributing#suggesting-new-methods).

Learn more about our goals and the way we work in our [wiki](https://github.com/18F/methods/wiki). 

## Development

### Running the Methods website on your local machine

#### Using Docker (recommended)

1. Install [Docker for Mac](https://docs.docker.com/desktop/install/mac-install/)
1. Clone this repository
1. From this repository's root directory, run `docker-compose up --build`
1. Open http://localhost:4000

#### Without Docker

You will need [Ruby](https://www.ruby-lang.org) ( > version 2.1.5 ). You may consider using a Ruby version manager such as [rbenv](https://github.com/sstephenson/rbenv) or [rvm](https://rvm.io/) to help ensure that Ruby version upgrades don’t mean all your [gems](https://rubygems.org/) will need to be rebuilt.

On OS X, you can use [Homebrew](http://brew.sh/) to install Ruby in `/usr/local/bin`, which may require you to update your `$PATH` environment variable:

```shell
$ brew update
$ brew install ruby
```

To serve 18F Methods locally, using `methods` as the name of your new repository:
Run each of the following steps to get the site up and running.

```shell
$ git clone git@github.com:18F/methods
$ cd methods
$ bundle install
$ jekyll serve
```

You should be able to see the site at: `http://localhost:4000/`

### Deploying

The Methods guide uses a webhook to deploy to Cloud.gov pages. When viewing a pull request, expand "Show all checks." If pages/build is complete, click "details" for a link to a preview for that branch.

## Current product owner
- Melissa Braxton


## Past contributors

- Tiffany Andrews
- Carly Jugler
- Megan Reed
- Peter Rowland
- Julie Strothman
- Anne Petersen
- Amirah Aziz
- Ana Monroe
- Jeremy Canfield
- Elisa Chen
- Erica Deahl
- Carolyn Dew
- Matt Dobson
- Andre Francisco
- Leah Gitter
- James Hupp
- Nicky Krause
- Omid Ghaffari-Tabrizi
- Julia Lindpaintner
- Colin MacArthur
- Andrew Maier
- Brad Nunnally
- Eric Richards
- Eric Ronne
- Jennifer Thibault
- Russ Unger
- Scott Weber
- Victor Zapanta

## Public domain

This project is in the worldwide [public domain](LICENSE.md). As stated in [CONTRIBUTING](CONTRIBUTING.md):
> This project is in the public domain within the United States, and copyright and related rights in the work worldwide are waived through the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).
>
> All contributions to this project will be released under the CC0 dedication. By submitting a pull request, you are agreeing to comply with this waiver of copyright interest.
