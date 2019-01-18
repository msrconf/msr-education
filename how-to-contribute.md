# Contributing

So you want to contribute to the MSR 2019 Education Track Educational Snippet Collection?

## What are we looking for?

Links, resources, videos, virtual machines, texts that can be used to help teach MSR to all sorts of students: undergraduates, graduates, postdocs, professionals, professors, etc.

The contributed snippets should be relevant to the field of mining software repositories.

The contributed snippets do not need to be your own resources. They can be links to resources you think are useful for educating students about MSR related topics. Be sure to attribute and credit the creators of the resources you link to.

Example topics stolen from the MSR 2019 CFP include:

* Analysis of change patterns and trends to assist in future development
* Analysis of natural language artifacts in software repositories
* Analysis of software ecosystems and mining of repositories across multiple projects
* Approaches, applications, and tools for software repository mining
* Characterization, classification, and prediction of software defects based on analysis of software repositories
* Characterization of bias in mining and guidelines to ensure quality results
* Empirical studies on extracting data from repositories of large long-lived and/or industrial projects
* Energy efficiency of software
* Meta-models, exchange formats, and infrastructure tools to facilitate the sharing of extracted data and to encourage reuse and repeatability
* Methods of integrating mined data from various historical sources
* Mining code review repositories
* Mining execution traces and logs
* Mining human and social aspects of development
* Mining interaction data repositories
* Mining mobile app stores and app reviews
* Mining multimedia repositories
* Mining software licensing and copyrights
* Models for social and development processes in large software projects
* Models of software project evolution based on historical repository data
* Prediction and modeling of software quality
* Privacy and ethics in mining software repositories
* Release engineering, including continuous integration, delivery and deployment
* Search-driven software development, including search techniques to assist developers in finding suitable components and code fragments for reuse, and software search engines
* [Software science](http://softwareprocess.es/blog/blog/2018/06/18/software-science-and-empirical-software-engineering/)
* Studies of programming language features and their usage
* Techniques and tools for capturing new forms of data for storage in software repositories, such as effort data, fine-grained changes, and refactoring
* Techniques to model reliability and defect occurrences
* Visualization techniques and models of mined data

## How to contribute?

Clone this repository yourself and create a new post in the ```_posts'''  directory.

* The post should be named _posts/YYYY-MM-DD-some-short-title.md 
* The post should be in markdown
* You should tell us who, what, where, and when (which MSR Education track)

Then you should commit all of that and make a pull-request on github against
this project. The administrators of the project will inspect your contribution
briefly and then accept the pull request or request clarification.

# Local use

Do you want to render the webpage at home and see what it looks like?

## Get the repository

Git clone the repo:

    git clone <repourl>/msr-education
    cd msr-education

## Install the horrendous ruby dependencies

Get bundler:

    gem install --user bundler
    # add the ruby bin to your PATH var
    # e.g.
    # export PATH=${HOME}/.gem/ruby/2.5.0/bin${PATH:+:${PATH}}
    bundle config bin  ${HOME}/.gem/ruby/2.5.0/bin
    bundle config path ${HOME}/.gem/ruby/2.5.0/

Then in the root of this repo type:

    bundle  install
    bundler update

Lots of horrible and horrendous ruby depdencies will be installed.

## Serve the page

    bundler exec jekyll serve 

Then go to [http://127.0.0.1:4000/](http://127.0.0.1:4000/)

## Share the joy 

Push your commits back to your repo. Make a pull request against our repo, describe your contribution and we'll publish it on our github page :)

## License

Please add your name and contact info to your post and share the post under the CC-BY 4.0 license with the project.
