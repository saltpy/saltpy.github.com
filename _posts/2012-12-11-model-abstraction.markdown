---
layout: post
title: Model Abstraction
---

{{ page.title }}
================

<p class="meta">11 Dec 2012 Leeds, UK</p>

Programs are data and operations on data. Everything that is valuable seems to be in linking those things. Building that abstraction between operations and data in a way that is efficent for rapid development and exposes the right things to test is very hard. Model objects can help by providing hooks to hang assertions on. 

A model object injects testability into a complex pipeline of objects or procedures by having a known state and solid means of reasoning about how the model got into that state. This model wraps up storage of form submissions and expected responses for a JUnit parameterized runner to come along and run all the tests. 

<script src="https://gist.github.com/4251215.js?file=ParameterModel.java"></script>

This simple model adds type safety and a degree of immutability. You can expand on this to enhance the quality of reporting in the parameterized runner or by wrapping some logging into the class. It has the use in development of forming information about a two key points in the world which makes debugging less likely to be needed - and we all know how hard debugging is.

I think using these model objects in your abstraction chain can provide the same effect as basing the whole chain on an interface while remaining closer to the real code running on the machine.
