# ***Overview***

Learning little small tricks list and keys provide using different methods are more time savers.  It really cuts down on writing out long codes, and helps keeps things dry.  The spread operator is another time saver.  Passing functions between components is good to know because a lot of the time if you can/'t get the specifics down on how to pass functions back and forth between parenst and children, you'll end up with a lot of headaches and error messages you'll have to go back and fix...killing time.


## ***Class 3 Assignment***

	1. What does .map() return?

map () returns a new array populated with the results of calling a provided function on every element in the calling array.

[Source: mdn web docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/map)

	2. If I want to loop through an array and display each value in JSX, how do I do that in React?

You must first render it in React by passing it through the DOM.

[Source: React](https://reactjs.org/docs/rendering-elements.html)

	3. Each list item needs a unique ____.

Key.

[Source: React](https://reactjs.org/docs/lists-and-keys.html)

	4. What is the purpose of a key?

Keys help React identify which items have changed, are added, or are removed.

[Source: React](https://reactjs.org/docs/lists-and-keys.html)

	5. What is the spread operator?

The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.

[Source: Medium.com](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

	6. List 4 things that the spread operator can do.

Copy an array, concatenate or combine arrays, use math functions, and use arrays as arguments.

[Source: Medium.com](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

	7. Give an example of using the spread operator to combine two arrays.

const myArr = ['a','b','c']
const yourArr = ['d','e','f']
const ourArr = […myArr,…yourArr]

[Source: Medium.com](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

	8. Give an example of using the spread operator to add a new item to an array.

const fewFruit = ['apple', 'orange', 'banana']
const fewMoreFruit = ['watermelon', 'pineapple', …fewFruit]

[Source: Medium.com](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

	9. Give an example of using the spread operator to combine two objects into one.

const objectOne = {hello: Hello}
const objectTwo = {world: world}
const objectThree = {…objectOne…objectTwo, excitement: !}

[Source: Medium.com](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

	10. In the video, what is the first step that the developer does to pass functions between components?

He created the function where the state lived he changed was.

11 .In your own words, what does the increment function do?

It loops through his array, finds the matching name and updates the count based on what's passed back into his ppl variable.

	12. How can you pass a method from a parent component into a child component?

Using this.state

How does the child component invoke a method that was passed to it from a parent component?

In the example he used this.props.increment(this.props.name)

[Source: Prof3ssorSt3v3](https://www.youtube.com/watch?v=c05OL7XbwXU)

## Things I want to know more about
