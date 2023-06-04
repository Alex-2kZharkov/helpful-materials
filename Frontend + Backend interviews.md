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
