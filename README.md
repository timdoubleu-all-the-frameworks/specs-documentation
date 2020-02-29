# All The Frameworks

## Table of Contents
1. [What is this org?](#about)
2. [Repositories Breakdown](#repos)
2. [Aspects of the application](#aspects)
3. [Interests tools/topics](#intrests)


<a name="about"></a>
## What is this organization?

This organization will build out a "specification" for a full stack application, writing up the documentation for an api and a frontend to consume that api. The organization will consist of repositories that implement that application in various technologies that I'm interested in. This documentation repository will be pinned to the top of the org and will consist of the specification for the application and quick documentation and direction about all the other repositories in this organization. Documentation specific to a technology will be in that specific repository.

The application will be fairly basic, however will make it slighty more complex than a trivial 'todo' app that are so common. I want to make the database relations more complex than just a single table, at least a few many to many relations. The reason for this is that, in my opinion, it's when you encounter complexity in your application that you are forced to make decisions on architecture and design that really gets you to "understand" the framework better. When building a simple single database table, single CRUD operations routes app like a todo list, you miss out on a lot of these.

The general idea will be a backend architected to produce a REST API built in a few languages that I'm interested in, for each language I'd like to try to build it without a framework and then again with a framework to help gain a deeper understanding of the problems that frameworks are giving you a solution for.

Then there will be front ends in various Javascript frameworks as well as non framework options such as jQuery and vanilla JS.


## Someone has already done this, you're so unoriginal!
Of course they have, there are a bunch of sites/projects of this type of idea all over the place, but being the one to actually build it yourself gives you experience that poking around on those sites can't. It's the different between just reading a programming book and writing a program. It also gives me the experience needed to factor out some boilerplate code to get up and running quickly if I ever want to reach for that language or the tools offered by that language for a real life project.

Other sites like this:
  1. [Todo MVC](http://todomvc.com/)


<a name="repos"></a>
## Planned Frameworks to be used

This is a list of difference languages or frameworks that I'd like to build out in the organization repositories.

### Backend

#### PHP
1. [Vanilla](https://www.php.net/)
1. [Slim](http://www.slimframework.com/)
1. [Laravel](https://laravel.com/)
1. [Lumen](https://lumen.laravel.com/)
1. [Symfony](https://symfony.com/)
1. [Silex](https://silex.symfony.com/)
    - Looks to be deprecated in favor of Symfony 4 and Flex.
1. [Laminas (formerly Zend)](https://getlaminas.org/)

#### Javascript
1. [Hapi.js](https://hapi.dev/)
1. [Express.js](https://expressjs.com/)
2. [Koa.js](https://koajs.com/)

#### Databases:
1. [Postgres](https://www.postgresql.org/)
1. [Mysql](https://www.mysql.com/)
1. [Sqlite](https://www.sqlite.org/index.html)


#### Devops/Server Setups:
1. [Virtual Box](https://www.virtualbox.org/)
1. [Vagrant](https://www.vagrantup.com/)
1. [Docker](https://www.docker.com/)
1. [Laravel Valet](https://laravel.com/docs/6.x/valet)
1. [Laravel Homestead](https://laravel.com/docs/6.x/homestead)

___

### Frontends

#### Static Sites:
1. [JAM Stack](https://jamstack.org/)
1. [Gatsby](https://www.gatsbyjs.org/)
1. [Next.js](https://github.com/zeit/next.js)

#### Javascript Frontends
1. [Vanille JS](http://vanilla-js.com/)
    - Doing modern state management and component type frontend stuff with mostly just pure DOM manipulation (Maybe some jquery)
    - [MobX, state management for vanilla JS](https://github.com/mobxjs/mobx)
1. [Preact](https://preactjs.com/)
1. [Svelte](https://svelte.dev/)
1. [React](https://reactjs.org/)
    - With and without Redux?
1. [Vue](https://vuejs.org/)
1. [Re:DOM](https://redom.js.org/)
1. [ReasonML](https://reasonml.github.io/)
1. [Elm](https://elm-lang.org/) 

#### Javascript Tooling
1. [Create React App](https://create-react-app.dev/docs/getting-started/)
1. [Rollup](https://rollupjs.org/guide/en/)
1. [Webpack](https://webpack.js.org/)
1. [Snowpack](https://www.snowpack.dev/)
1. [Parcel](https://parceljs.org/)
1. [Rome](https://github.com/facebookexperimental/rome)



___

Unplanned, Languages I don't use but have heard good things about and want to try out:

#### [Elixir/Erlang](https://elixir-lang.org/):
1. [Pheonix Framework](https://www.phoenixframework.org/)
    - [Pheonix MVP Tutorial](https://news.ycombinator.com/item?id=19971456)

#### Python:
1. Plain Python
1. Flask
1. Django

#### Go:
1. Revel
1. Plain Go

#### Rust
1. TBD





<a name="aspects"></a>
## Aspects to be covered with each framework
1. Database design
1. Database ORM Scripts
1. RESTful API Routing
1. Authentication for the API
1. Frontend application to consume the API
  - SPA version ?
  - SSR version ?
1. Design Patterns
  - [Domain Driven Design](https://airbrake.io/blog/software-design/domain-driven-design)
1. Repository Setup
  - Git Branching Strategy,
  - Release Strategy and Tagging
  - Frontend and backend code in same repo or shared repos
    - https://stackoverflow.com/questions/30628356/manage-project-backend-and-frontend-in-two-separate-branches-or-repositories


<a name="intrests"></a>
