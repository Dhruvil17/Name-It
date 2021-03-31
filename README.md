# Name It

Ideate, Design, Build are basically main steps to build any Project. 

Step 1: Ideate
Step 2: Rough Sketch
Step 3: Wireframes
Step 4: Design the screens
Step 5: App Architecture
Step 6: Flow/Sequence Diagrams

# Component: Any visual component that you can see on your screen is basically called the React Component. 

### Components used in this Name It Project. 
1. Container Component - App (Outer)
2. Header Component
3. Search Box Component
4. Results Container Component - NameCard Component

Always create a Component Architecture to visualize the flow of our App or React Website. 

Direct data flow between Sibling Components is not possible in React. 

1st Command used at starting - npx create-react-app nameit

Create React App - Gives us a BoilerPlate

### What is JSX
Combination of JavaScript and HTML. 

### There are 2 types of Components
1. Class Based
2. Functional Component

#### State
Piece of data that you might need to save that might change in future. (JavaScript Object)
React uses JavaScript object to implement state. 
Changing the piece of text inside the state, does not re-render it hence it is not updated on our screen. 
To re-render it, use setState() property. 

#### Props
It is a kind of data that we can transfer, transport or communicate from our parent component to the child component. 

Parent to Child data flow is done using Props
Child to Parent data flow is done using Callback method
