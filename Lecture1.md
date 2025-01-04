/* # Lecture 1

# React 18 new features

- Concurrent React
- Automatic Batching
- Transitions
- New Suspense Features
- Client and Server Rendering API’s
- Strict Mode Behaviours
- New Hooks
    - useId
    - useTransition
    - useDeferredValue and more..
- Routing V6

- we will do a MERN stack application at the end of the course

# What will we learn ?

- React 17 and 18 with new features (with JavaScript and Typescript)
- Redux
- React Native
- Introduction to various Tool chains

# Next.Js

- **Next.Js** is a popular and lightweight framework for static and server-rendered applications built with React. It includes styling and routing solutions out of the box, and assumes that you’re using Node.js as server environment.

# Gatsby

- **Gatsby** is the best way to create static websites with React. It lets you use React components, but output pre-rendered HTML and CSS to guarantee the fastest load time.
- **Neutrino** combines the power of webpack with the simplicity of presets, and includes a preset for React apps and React components.
- **Nx** is a toolkit for full-stack monorepo development, with built-in support for React, Next.js, Express and more.
- **Parcel** is a fast, zero configuration web application bundler that works with React.
- **Razzle** is a server-rendering framework that doesn’t require any configuration, but offers more flexibility than Next.js
- react is used with all the above.

- What is React? why we need React?
- What are the challenges in modern web development?
    - Modern web users are using web from smart devices. (more than 80%)
    - unified UX (an application must have same behaviour across any device)
    - fluid UX
    - neloosely coupled and extensible architecture

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e6e3128e-057b-4a4e-9f53-ed1f2dd7c8e2/c74e84a6-0198-4c44-ac6e-e8b3da9acf63/image.png)

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/e6e3128e-057b-4a4e-9f53-ed1f2dd7c8e2/3de8e0a1-871a-4ab0-a3b1-10d58309d16b/image.png)

- In early days, for mobile devices application is optimized / compressed. After optimizing some features are not working in mobiles and some are working. But we want the application to have same user experience in mobile too. This is called unified user experience.
- Fluid user experience means coming everything in a single page. ex: image section.
- loosely coupled and extensible: adding features to the application without the need of installing the application again and without stopping the application (for some seconds the app will be idle and we will push new features to the application).

 

- What is solution (to overcome all these issues)?
    - Better to build SPA (single page applications). SPA have Unified UX, fluid UX and loosely coupled and extensible architecture.
- Difference between SPA and ordinary application?
    - In SPA ex: login page is not designed as separate page. It is embedded in same page as component.
    - components are present in JavaScript also.
- How to build SPA?
    - we can build SPA with JS and JQuery
- what are the issues with JavaScript and JQuery?
    - Lot of DOM manipulations
    - Lot of references
    - Lot of coding
    - Lot of event handling
    - Lot of explicit Ajax
- What is solution to JS and JQuery?
    - better use library or framework
    - React, Angular, Vue, Ember, BackBone, Knockout
    - React → facebook community, angular → google
- What is React?
- React vs Angular?
*/