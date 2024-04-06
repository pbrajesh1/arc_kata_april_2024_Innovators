# Title: Choose frontend framework for single page application

## Status

APPROVED

## Context

We are developing a single page fronend application that requires a rich and interactive user interface. We need to choose a frontend framework that can help us create a fast, scalable, and maintainable web application.


## Decision

* We have decided to use Angular as our frontend framework over React. 
* Angular is a TypeScript-based, open-source web application framework led by the Angular Team at Google and by a community of individuals and corporations1. 
* React is a JavaScript library for building user interfaces, created by Facebook2.

We have chosen Angular over React for the following reasons:

* Angular is a full-fledged MVC framework that provides built-in features such as routing, form validation, HTTP handling, dependency injection, and more1.
* Angular provides more structure and guidance for developing complex applications, while React gives more flexibility and freedom for developers to choose their own tools and architecture.
* Angular uses TypeScript, which is a superset of JavaScript that adds static typing and other features1. TypeScript can help us catch errors at compile time, improve code readability and maintainability, and enable better tooling and IDE support3. React uses JavaScript by default, but can also be used with TypeScript or other transpilers such as Babel2. However, using TypeScript with React may require additional configuration and setup4.
* Angular has a faster initial rendering performance than React, as it uses ahead-of-time (AOT) compilation to convert TypeScript code into native JavaScript code before the browser downloads and runs it.
* Angular has a better support for progressive web apps (PWAs), which are web applications that can work offline, load faster, and behave like native apps on mobile devices. 
* Angular has a built-in service worker module that can handle caching, background sync, push notifications, and other PWA features. React does not have a built-in support for PWAs, but can use third-party libraries or tools such as Create React App or Next.js to create PWAs.


## Consequences

By choosing Angular over React, we will have the following implications:

* We have skill resources in Angular which will come in handy.
* We will have to follow Angular’s opinionated structure and best practices, which may limit our creativity and flexibility in some cases. However, we can also benefit from Angular’s consistency and stability in developing large-scale applications.
* We will have to use Angular’s built-in tools and libraries for most of the features we need, which may reduce our dependency on external sources. However, we can also use third-party libraries or tools if we need more customization or functionality that Angular does not provide.
* We will have to update our code regularly to keep up with Angular’s frequent releases and changes, which may introduce breaking changes or deprecations. However, we can also benefit from Angular’s new features and improvements that enhance the performance and usability of our web application.


[Home Page](../README.md) | [ADR Home Page](../Architecture_Decision_Reports)