---
layout: post
title: How to use Sentry for profiling a test suite.
date: 2021-09-21 18:00:47 +0100
medium_url: https://dev.to/potloc/how-to-use-sentry-for-profiling-a-test-suite-30l7
lang: en
---

At Potloc one of our core values is learning, that's why each quarter the development team has a dedicated time to explore new things. This aptly named Dev Happiness Week allows us to tackle either a new pattern, open source project, write a blog post and so on.
One of my initial projects was to monitor our test suite. The more our test suite was growing quickly the more seconds were added to our CI. But without any monitoring on how long each test takes to run it was complicated to identify and speed up the slowest ones...
