title: >-
  Building an application with Angular2, Dotnet Core, Web API and Entity
  Framework
author: Trevor de Koekkoek
date: 2016-12-08 21:48:24
tags:
---
This is the first in a multi-part blog series where I will discuss building an application using Angular2, Typescript, Webpack, .NET Core, Web API and Entity Framework.

# Introduction
I tend to skip through long blog posts, espcially those littered with screenshots of Visual Studio dialogs or similar.  I like to get to the point when reading blogs and aim to do the same when writing them.  That said, the series wouldn't be complete without a brief introduction to each of these technologies.

## Technologies We're Using:

* Angular2
Angular has been an extremely popular framework for building the client side of web applications, typically of the single page variety (SPAs) as well as being the core behind the popular mobile framework, Ionic.  Now in version 2, this popular framework has become even more powerful allowing you to build applications using modern javascript (ES5, ES6) and Typescript while utilizing modern application concepts like Web Components.  Ionic 2 has also followed suit.  For more information see http://angular.io

#### TypeScript
TypeScript has become an indespenable tool for probably the majority of Javascript developers.  While some prefer to work in straight javascript, the benefits of typed Javascript have become extremely compelling.  Unlike pre-comilers like CoffeeScript, TypeScript is a pure superset of JavaScript.  And while developed by Microsoft it has been fully empraced by Google, who, at least for Angular 2 has actually endorsed it in favor of their own pre-compiler known as Dart.  For more information see https://www.typescriptlang.org/

#### Webpack
Early releases of Angular focused on System.js for module loading.  Since then, the Angular team has fully embraced Webpack which has become the tool of choice for build scripting, bundling and module loading.  Honestly Webpack is a big topic that I'm only beginning to grasp so I will give a brief introduction to this topic.  For more information see http://webpack.github.io/

#### .NET Core
.NET is a huge subject and no-doubt if you're reading this you are very familiar with it.  .NET Core is its newest incarnation and is the first version that can run cross-platform.  As long as we don't need any features in standard .NET, I'd like to build the application in .NET Core even though I will most likely only be hosting the application on Windows.

#### Web API
.NET Web API is the server-side technology that we'll use to create your REST server.  There are many other choices that we could have used such as Node.js or Java, but for me .NET Web API is a powerful choice that lets us develop our backend quickly while utilizing a language that I know very well, C#.

## Entity Framework
We'll be building out our persistence using Entity Framework and SQL Server.  I'll briefly cover Code first migrations and how to build a data access layer using Entity Framework and how to provide that our Web API layer.