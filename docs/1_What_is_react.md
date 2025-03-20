# **Introduction**
## **Vanilla JS: A definition**

- Using JS alone is reffered to as Vanilla JS.
- Requires rewriting code for functions every time they occur.

- Using "Just Javascript" typically isn't a great option.
    - Writing complex Js code quickly becomes `cumbersome`.
    - Complex JS code quickly becomes `error-prone`.
    - Complex JS code is often is `hard to maintain or edit`.
    - Managing the `state of an application can become complex` as the application grows.

## **JavaScript Libraries**
- **JavaScript libraries** are collections of prewritten code snippets.
  - Used to perform common JavaScript functions.
  - Can be reused in different parts of a project.
- Library code can be integrated into a project on an "as needed" basis.
- Libraries are specialized tools for specific coding needs.
- They are not all-in-one tools or templates for formatting an entire project.

**Examples of JavaScript Libraries**
- jQuery
- React JS

## **Javascript Frameworks**
- **JavaScript frameworks** are a full toolset that help shape and organize your website or web application.
- Frameworks provide a structure (skeleton/scaffolding) to base your entire project around.
- Frameworks offer page templates with specific areas for inserting framework code.
  - Contrasts with libraries where the developer decides where to implement the code.

**Examples of JavaScript Frameworks**
- Angular
- Ember JS
- Vue

## **Analogy**
Library|Framework
--------|--------
like pieces of furniture that add style and function to an already constructed house. | like a template used to build the house itself.
Can be used with any project, offering specific functionalities. | Requires following rules and conventions specific to the framework.
Provides more freedom in choosing how to implement functionalities. | Limits the freedom compared to using a library.
You call the library code in your application. | The framework calls your code in a predefined way.

# **React = Declarative UI Programming**

- With react, you define the target UI state(s) - not the steps to get there.
- Instead, React will figure out & perform the necessary steps.

![Declarative and Imperative](/assets/md/1_declarative-ui-programming.png)

# Components
- Independent and reusable bits of code.
- Serve the same purpose as JS functions but work in isolation and return HTML.

## **Class Component**
```jsx
class displayHelloWorld extends React.Component {
  render() {
    return <h2>Hello, World</h2>
  }
}
```

## **Function Component**

```jsx
function displayHelloWorld() {
  return <h2>Hello, World!</h2>
}
```



