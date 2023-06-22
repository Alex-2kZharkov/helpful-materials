# React.js

## Topics

- **State vs Props**
  - Immutable aspect: Props or State?
- **Component Re-rendering**
  - Instances where a component gets re-rendered? (State changes, Props changes, Context changes, this.forceUpdate)
- **useHistory**
  - Purpose of useHistory?
- **State Manager**
  - Advantages of state manager.
- **State**
  - How does state work: Synchronously or Asynchronously, and why is it implemented that way?
- **Context**
  - Actions required to use context?
- **Synthetic Events**
- **Pure Component**
- **Fragment**
- **useCallback and useMemo**
  - Differences between useCallback and useMemo.
- **Controlled and Uncontrolled Components**
- **Ref**
  - Purpose of Ref?
- **Debugging**
  - How do you debug React applications?
- **Typechecking for Props**
  - Typechecking for props in functional components.
- **querySelector**
  - Drawbacks of using querySelector.
- **useLayoutEffect and useEffect**
  - Difference between useLayoutEffect and useEffect.
- **Custom Hooks**
- **React Application Architecture**
  - Feature sliced, atomic design.
- **useEffect**
  - What happens if useEffect does not pass dependencies?
- **Testing**
  - What kind of tests do you write? What technologies do you use for testing? How do you compose unit tests?
- **React.memo**
  - Purpose of React.memo?
  - React.memo with object/functions as props?
- **Batching**
- **Error Boundaries**
  - How to create one?
- **Identification, Authentication, Authorization**
  - Difference between identification, authentication, authorization.
- **requestAnimationFrame**
  - Higher priority rendering?
- **requestAnimationIdle**
  - Lower priority rendering?

## React 18

- **Concurrency**
- **Batching**
- **New APIs**
- **New Hooks**
- **Suspense Component**
- **Transitions**
- **Strict Mode**
- **Optimization in React.js**
  - React.memo, useMemo, useCallback, PureComponent, shouldComponentUpdate, state separation, context separation
- **React.memo vs PureComponent**
- **Reconciliation in React**
- **Fiber in React**
- **Patterns in React**
  - HOC, composition, provider with context, hooks, compound components, render props
- **Snapshots in React**

## Redux

- **Data exchange/State update in Redux**
  - Do you mutate the store directly? How then is the store updated?
- **Reducer Function**
  - What rules should be followed when writing a reducer function?
  - Who/What calls the reducer function?
- **Asynchronous Logic in Middleware**
  - Why is asynchronous logic put into middleware, for example, thunks?
- **State Retrieval from Store**
  - What allows retrieving the current state from the store?
- **Observer Pattern**
- **Redux Toolkit**
  - What is Redux Toolkit? What problems does it solve?

## React-router

- **BrowserRouter**
  - Why wrap the entire component tree in BrowserRouter? Difference between BrowserRouter and HashRouter
- **Route Components in Switch**
  - Why wrap Route components in Switch?
- **Route Navigation**
  - How to navigate the user to a new route?
- **React-router Hooks**
  - What other hooks are there for working with react-router?


# Frontend

## Topics

- **Critical Rendering Path**
- **Blocking JS Files**
- **CSS in JSS | Styled Components**
  - Pros/Cons of CSS in JSS | Styled Components
- **Performance Improvement Tactics**
- **Virtualization in Frontend**
- **Reflow and Repaint**
- **Shadow DOM**
- **Repaint, Reflow**
- **RAIL Model**
- **Service Workers**
- **Event Propagation**
  - Event bubbling
  - Event capturing
- **Sass/Less**
  - Benefits of using Sass/Less
- **Domain Name Input Process**
  - What happens when you type a domain name in the address bar and how does a browser render the page?
- **requestAnimationFrame**
- **CSS Styles Rendering**
  - How are styles rendered, prioritized selectors in CSS?
- **Event Loop**
- **Animations**
  - Animations with transition and animation frames
- **HTTP/HTTPS**
- **Async/Defer Script Modifiers**

## Webpack

- **Bundling**
- **Create React App (CRA)**
  - Pros and Cons of CRA
  - Eject in CRA
- **Cyclic Dependencies**

# Functional Programming

## Topics

- **Pure Functions**
  1. Input -> Output
  2. No side effects (side effect is everything besides calculating result based on parameters)
  3. No global variables
- **Higher-order Functions**
- **Array Methods vs 'for' Iteration**
- **Immutability**
  - Don't use mutable data. Immutable.js and data structure optimized for immutable operations
- **First-class Functions**
- **Currying**
- **Functional Composition**
- **Functional Programming Libraries in JavaScript**
- **Lambdas**

# General/Architecture

## Topics

- **High Cohesion, Low Coupling**
- **SOLID in React and OOP**
- **DRY**
- **KISS**
- **YAGNI**
- **APO (Avoid Premature Optimization)**
- **Clean Code**
- **OOP**
- **Functional Programming**
- **Testing**
  - Testing pyramid. White box, black box, gray box testing.
  - Unit tests (FIRST principle), integration tests, e2e tests
- **Choosing NPM Libraries**
  - How do you choose an npm library?

## Design Patterns

- **Command**
- **Observer**
- **Dependency Injection**
- **Decorator**
- **Prototype**
  - [Prototype Pattern](https://www.patterns.dev/posts/prototype-pattern)
- **Proxy**
- **Facade**
  - [Facade Pattern](https://refactoring.guru/design-patterns/facade)
- **Singleton**
  - [Singleton Pattern](https://refactoring.guru/design-patterns/singleton)
- **Module Pattern in JS**
  - [Understanding Design Patterns in JS](https://blog.bitsrc.io/understanding-design-patterns-in-javascript-13345223f2dd)
- **Factory**
  - [Understanding Design Patterns in JS](https://blog.bitsrc.io/understanding-design-patterns-in-javascript-13345223f2dd)
- **Abstract Factory**
  - [MVC vs MVP vs MVVM](https://levelup.gitconnected.com/mvc-vs-mvp-vs-mvvm-35e0d4b933b4)


# REST API

## Topics

- **Key Principles of RESTful Architecture**
  - [RESTful API](https://restfulapi.net/)
- **HTTP Methods**
- **HTTP 2**
- **Idempotency**
- **CORS**
  - As much detail as possible about CORS
- **Cookies**
  - How does the secure flag work? The httpOnly flag? Why is it good practice to change cookies only on the BE?
- **HTTP vs HTTPS**
  - Difference between HTTP and HTTPS
- **Web Sockets vs Polling**
- **Long Polling vs Short Polling**
- **Content Security Policy (CSP)**
- **OAuth vs OAuth 2 vs OpenID**
- **JWT**
  - What is JWT? What does it consist of? Where in the request is it sent? How to invalidate a JWT token?
- **Sessions**
  - How do they work? How to implement?
- **SessionId vs JWT**
  - Why would you prefer SessionId to JWT and vice versa?

# TypeScript

You can find more information about TypeScript on [Total TypeScript](https://www.totaltypescript.com/).

## Topics

- **Type Annotations** (TS 1.0)  
  `let name: string = "John";`

- **Interfaces** (TS 1.0)  
  `interface Person = { name: string }`

- **Type Aliases** (TS 1.0)  
  `type ID = string | number;`

- **Union Types** (TS 1.4)  
  `let value: string | number = "abc";`

- **Generics** (TS 1.0)  
  `function identity<T>(arg: T): T { return arg; }`

- **Intersection Types** (TS 1.6)  
  `type EmployeeInfo = Person & Employee;`

- **Enums** (TS 2.4)  
  `enum Direction { Up, Down, Left, Right, }`

- **Type Assertions** (TS 1.0)  
  `let value: any = "hello"; let length: number = (value as string).length;`

- **Nullish Coalescing Operator** (TS 3.7)  
  `let result = input ?? defaultValue;`

- **Optional Chaining** (TS 3.7)  
  `let value = obj?.prop?.[index];`

- **Tuple Types** (TS 1.3)  
  `let tuple: [string, number] = ["hello", 42];`

- **Void Type** (TS 1.0)  
  `function log(message: string): void { console.log(message); }`

- **Unknown Type** (TS 1.0)  
  `let name: unknown`

- **Never Type** (TS 2.0)  
  `function throwError(message: string): never { throw new Error(message); }`

- **Type Guards** (TS 1.6)  
  ```typescript
  function isString(value: any): value is string {
    return typeof value === "string";
  }
- **Non-null Assertion Operator (TS 2.0)**
  `let value: string = someOtherString!;`
- **keyof Operator** (TS 2.1)
  ```
  interface Person {
    name: string;
    age: number;
  }
  let key: keyof Person = "name";
  ```
- **Mapped Types (TS 2.1)**
```
interface Person {
  name: string;
  age: number;
}

type ReadonlyPerson<T> = {
  readonly [P in keyof T]: T[P];
};

let readonlyPerson: ReadonlyPerson<Person> = {
  name: "John",
  age: 30,
};
```
- **Recursive Types (TS 3.7)**
  ```
  type TreeNode = {
  value: string;
  left?: TreeNode;
  right?: TreeNode; 
  };
  ```
- **Internal Namespace (TS 1.5)**
```
  namespace MyNamespace {
  export const myVar: string = "Hello";
  export function myFunc(): void {
    console.log(myVar);
  }
}

console.log(MyNamespace.myVar); // Output: "Hello"
MyNamespace.myFunc(); // Output: "Hello"
```
  
- **Ambient Namespace (TS 1.4)**
```
  declare namespace MyLibrary {
  function myFunc(): void;
  const myVar: string;
}

MyLibrary.myFunc();
console.log(MyLibrary.myVar);
```

# **Немного CI/CD**
_Больше для начинающих, но может поможет освежить память_

## **Метрики**
- [GitLab CI/CD Metrics](https://about.gitlab.com/topics/ci-cd/continuous-integration-metrics/)

## **Containerizing Node.js Web Applications with Docker**
- [10 Best Practices - Snyk](https://snyk.io/blog/10-best-practices-to-containerize-nodejs-web-applications-with-docker/)

## **Continuous Integration, Delivery, and Deployment**
- [Principles: CI vs CD vs Deployment - Atlassian](https://www.atlassian.com/continuous-delivery/principles/continuous-integration-vs-delivery-vs-deployment)
- [Tutorials - Atlassian](https://www.atlassian.com/devops/continuous-delivery-tutorials)
- [CI/CD Overview - GitLab](https://about.gitlab.com/topics/ci-cd/)

## **Стратегии деплоя**
- [Deployment Strategies - The New Stack](https://thenewstack.io/deployment-strategies/)

# **Node.js**

## **Node.js General**
- [DigitalOcean Tutorials - Node.js](https://www.digitalocean.com/community/tutorials?hits_per_page=12&q=%5BNode.js%5D)
- [Wanago.io](https://wanago.io/)

### **Вопросы**
- В чем разница между nodejs и javascript?
- Node.js работает ассинхронно или парраллельно?
- Как вы понимаете термин: non-blocking, event-driven?
- Для каких проектов/задач лучше использовать node.js и почему?
- Расскажите как устроен event loop в nodejs.
- Расскажите о libuv.
- What is the difference between a synchronous and asynchronous function in Node.js, and when would you use each of them?
- Как вы понимаете, что вам нужна npm библиотека и выбираете ее?
- [setImmediate, nextTick](https://nodejs.org/en/docs/guides/event-loop-timers-and-nexttick/)
- Event Emitter in Node.js
- [Streams in Node.js](https://nodejs.dev/en/learn/nodejs-streams)
- Buffers in Node.js
- Разница между несколькими потоками (threads) и процессами. Типы стримов.
- [Worker thread](https://www.digitalocean.com/community/tutorials/how-to-use-multithreading-in-node-js), [piscina](https://www.npmjs.com/package/piscina?activeTab=readme)
- [Child processes](https://www.digitalocean.com/community/tutorials/how-to-launch-child-processes-in-node-js)
- [Cluster mode](https://www.digitalocean.com/community/tutorials/how-to-scale-node-js-applications-with-clustering)
- На что обратить внимание при оптимизации приложений на node.js?
- Don't block the event loop
- Prefer native JS methods over user-land utils like Lodash
- Error handling
- What is event-driven programming in Node.js, and how does it differ from traditional request-response models?
- How do you ensure the security of your Node.js applications and prevent common vulnerabilities such as SQL injection or cross-site scripting (XSS)?
- Node.js + Rabit [Asynchronous Tasks with Node.js and BullMQ](https://www.digitalocean.com/community/tutorials/how-to-handle-asynchronous-tasks-with-node-js-and-bullmq)

# **Express.js**

## **Вопросы**
- Почему хорошая практика это разделять server и app в express?
- Что должен содержать server?
- Что должен содержать app?
- Как работает/организовать роутинг в express?
- Что такое middleware?
- Какие типы middleware существуют? С какими работали?
- Error handling в express?
- Если расположить загрузку middleware после роутов, сработает ли это middleware? Что сделать, чтобы расположенное после роутинга middleware отработало?
- Как/где установить middleware для единичного роута?
- Назовите сторонние/third-party middleware.
- Каким образом управление переходит из одного middleware в другой?
- Какие параметры принимает middleware?
- Как разрешить использование CORS в express?
- Как бы организовали файловую структуру на сервере с express?
- Как увеличить безопасность express приложения?
- Семантическая разница между Patch and Put Http методами.
- Как работать со статикой в express? Как при этом не деградировать в performance?
- Как деплоите?
- В чем различие между хэшированием и шифрованием?
- Расскажите о SOLID.
- Difference between express and NestJS.

# **Section 1: SQL Basics**

## **Questions**
- What is SQL, and what is it used for?
- What are the different types of SQL commands?
- What are the different data types in SQL?
- What is a primary key, and why is it important? What are the best practices for choosing a primary key?
- What is a foreign key, and how does it relate to a primary key?
- What is a join, and how is it used in SQL? What types of joins do you know?
- What is the difference between, LEFT, RIGHT, INNER and OUTER joins in SQL, and when would you use each?
- What is a SQL constraint, and what are the different types of constraints available in SQL?
- What is a transaction in SQL, and why is it important?
- How do you use the GROUP BY clause in a SQL query, and what does it do? What aggregation functions do you know, and how do they work?
- How do you use the HAVING clause in a SQL query, and what does it do?
- What does DISTINCT operator do? How is it different from GROUP BY What pitfalls does it have?
- How do you write a subquery in SQL, and what is it used for?

# **Section 2: Relational Database Design**

## **Questions**
- What is normalization, and why is it important in database design?
- What are the different normal forms in database normalization? Tell about first 3 normal forms
- How do you create a table in SQL, and what are the different options available when creating a table?
- What is a view in SQL, and how is it different from a table?
- What is a composite key in SQL, and when would you use it?
- What is referential integrity, and how is it enforced in a SQL database?
- What is the difference between a view and a materialized view in SQL, and when would you use each?
- What is data isolation?

# **Section 3: Advanced SQL Concepts**

## **Questions**
- Transaction models (ACID vs BASE)
- How do you use the UNION and UNION ALL operators in a SQL query, and what is the difference between them?
- What is a stored procedure, and how is it used in SQL? What are the best practices for creating a stored procedure?
- What is a trigger, and how is it used in SQL? What are the actions triggers can be applied to?
- What are the different types of SQL functions, and how are they used?
- What is the difference between a scalar and table-valued function in SQL, and when would you use each?
- What is the difference between a correlated and non-correlated subquery in SQL, and when would you use each?
- What is a CTE (Common Table Expression) in SQL, and how is it used?
- How do you use the EXISTS operator in a SQL query, and what does it do?
- How do you use the CASE statement in a SQL query, and what is it used for?
- How do you use the ROW_NUMBER function in a SQL query, and what is it used for?
- What is a temporary table in SQL, and how is it used?
- How do you use the MERGE statement in SQL, and what is it used for?
- What is a dynamic SQL query, and how is it different from a static SQL query?
- How do you use the EXCEPT and INTERSECT operators in a SQL query, and what do they do?

# **Section 5: SQL Optimization**

## **Questions**
- How do you optimize a SQL query, and what are some common techniques for doing so?
- What is query plan, and how can it be used to optimize SQL queries?
- How do you use the EXPLAIN command in SQL, and what does it do?
- How do you use the ANALYZE command in SQL, and what is it used for?
- What is an index in SQL, and how is it used to improve query performance? Which fields should you cover with indexes?
- What is the difference between a clustered and non-clustered index in SQL, and when would you use each?
- What is a covering index in SQL, and how can it improve query performance?
- What is a full-text index, and how is it used to improve query performance in SQL?
- How do joins affect query performance?
- What is a materialized view, and how can it be used to improve query performance?
- How do you monitor SQL database performance, and what are the different metrics you should track?
- What is partitioning? What is sharding?
- What is a query hint, and how can it be used to optimize SQL queries?
- How do you use the STATISTICS IO command in SQL, and what does it do?
- What is query optimization, and how does it differ from query tuning?
- How do you use the SET statement in SQL, and what are some best practices for using it?
- What is a query plan cache, and how can it be used to improve query performance in SQL?

# **Section 6: Database Administration**

## **Questions**
- Чем DDL отличается от DML? Что такое TCL, DCL, DQL?
- What are the different tools available for managing SQL databases?
- What is a backup in SQL, and how can it be used to prevent data loss?
- What are the different types of database backups, and when would you use each?
- What is a restore in SQL, and how can it be used to recover lost or damaged data?
- What are the different security considerations when managing a SQL database, and how do you address them?
- What is a database transaction log, and how can it be used for data recovery and replication?
- What is the purpose of the PostgreSQL configuration file, and how can it be used to configure the database server?
- What are the different authentication methods in PostgreSQL, and how do you configure them?
- How do you manage user accounts and permissions in PostgreSQL, and what are some best practices for doing so?
- What is a PostgreSQL extension, and how can it be used to extend the functionality of the database server?
- What is a database cluster in PostgreSQL, and how is it used to distribute data across multiple servers?
