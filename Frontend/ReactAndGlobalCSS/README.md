## Working with Global CSS in React and React Native

#### by Tenji Tembo

**Summary**

React is one of the most popular Front end frameworks in the modern web. It's component-first philosophy drives the direction and consistency of the platform, include areas such as CSS. So much so that CSS is "componentized" into React files and left unable to take advantage of more global elements found in more custom css libraries, such as heavily modified Bootstrap Libraries. In this talk, I'll talk about the available cohesion of using globally available CSS libraries, while still giving overall control to the component referenced via state management.

_I'll break down the following:_

- Global CSS Libraries
  - The history of CSS setups in traditional monolith setups
  - What do they do well
    - centralized location
    - use of preprocessors (SASS/LESS) for better management
  - What they do poorly
    - less freedom in more one-off CSS setups due to existing CSS definitions
    - new CSS can override existing CSS and cause visual errors or behavior
    - just like the monolith they reside in, size can greatly increase
- Current CSS Practices in React/React Native
  - Inline CSS: keeps in in the component, more global-oriented elements must be redefined
  - CSS Modules: more declarable snippets and locally scoped. but no global scope requires multiple declarations across components
- Can you have both?
  - Of course! Manage the base globally available CSS to support a "minimum spec"
    - Minimum Spec CSS: Fonts, Colors, Sizes, Grid, Responsive Breakpoints, and other Declarations
    - Modular CSS: More specialized CSS for each declared component
- Extending manageable CSS via State management

**Extra Content:**
- [Google Docs Abstract](https://docs.google.com/a/mustwin.com/document/d/1PmNVh1d4tfO93mAtVJmc7RrdtSd4CKixE7Mfv_xMzLA/edit?usp=sharing)
