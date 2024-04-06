# Title: Use Django and python for analytics and reporting

## Status

APPROVED

## Context

We are developing a service that requires analytics and reporting features. We need to choose a programming language and a framework that can support these features and facilitate the development of the application.


## Decision

* We decide to use Python and Django for our analytics and reporting application. 
* Python is a powerful, expressive, and versatile programming language that supports multiple paradigms, such as object-oriented, functional, and procedural. 
* It has a large and active community of developers, a rich set of libraries and modules, and a high level of readability and maintainability. 
* Django is a high-level web framework that follows the model-view-template (MVT) pattern. It provides features such as rapid development, clean design, security, scalability, and database abstraction. 
* Django also integrates well with various data sources, tools, and libraries that can be used for analytics and reporting.


## Consequences

By using Python and Django for our analytics and reporting application, we can expect to achieve several benefits, such as:
* We can create our application quickly and easily by using the built-in features and components of Django. We can also use the Django admin interface to manage our data and users.
* We can perform data analysis and visualization tasks in Python by using the available libraries and modules, such as pandas, numpy, matplotlib, seaborn, etc. We can also use the Google Analytics API to access and manipulate our web analytics data in Python.
* We can add interactive dashboards and charts to our application by using JavaScript libraries such as Flexmonster Pivot Table & Charts or Chart.js. 
* We can write clean, readable, and maintainable code in Python by following the PEP 8 style guide and using tools such as PyCharm .
However, we also need to be aware of some challenges or trade-offs that we may face by using Python and Django for our analytics and reporting application, such as: * We need to have a good understanding of the concepts, principles, patterns, and best practices of web development and data science. 
* We also need to be familiar with the various components, dependencies, configurations, and conventions of Django and the libraries we use. 
* We may experience some performance issues due to the interpreted nature of Python and the dynamic typing system. 
* We may also have some additional dependencies and modules that may increase the memory footprint and loading time of our application.

[Home Page](../README.md) | [ADR Home Page](../Architecture_Decision_Reports)