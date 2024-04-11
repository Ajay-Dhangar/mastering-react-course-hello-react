# Creating a simple React component

Let's create a simple React component using JSX and functional components. We will create a component that displays a greeting message.

1. Create a new file named `Greeting.js` in your React project.
2. Add the following code to define the `Greeting` component:
	
	```jsx
	import React from 'react';

	 function Greeting() {
		return <h1>Hello, React!</h1>;
	 }
	
	 export default Greeting;
	```

3. Import and use the `Greeting` component in your main application file (e.g., `App.js`):
	```jsx
	import React from 'react';
	import Greeting from './Greeting';

	function App() {
		return (
			<div>
				<h1>Welcome to React!</h1>
				<Greeting />
			</div>
		);
	}

	export default App;
	```
	
4. Run your React application to see the Greeting component in action.
5. You should see the greeting message "Hello, React!" displayed on the screen.
6. Congratulations! You have created your first React component using JSX and functional components.