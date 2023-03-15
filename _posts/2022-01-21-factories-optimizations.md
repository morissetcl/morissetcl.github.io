---
layout: post
title: How to optimize factory creation.
date: 2022-12-13 18:00:47 +0100
medium_url: https://dev.to/potloc/how-to-optimize-factory-creation-3bnp
lang: en
---

At Potloc we have a test stack which is pretty standard in the Rails ecosystem. We run tests with RSpec, we use FactoryBot for setting up our test data, Capybara for user interactions, Github Actions as a CI etc..These great tools allow us to code at a fast pace with good test coverage. But this pace comes at a cost. The more the team grows, the bigger the codebase gets and the more tests get written.
