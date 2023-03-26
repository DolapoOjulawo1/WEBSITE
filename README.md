QUESTION 2: List five significant features of React
ANSWERS:
a.JSX (JavaScript Syntax Extension)
b. Components
c. One-way Data Binding
d. Virtual Document Object Model (VDOM)
e. Performance.


QUESTION 3: List five major advantages of React
ANSWERS:
a. React is easy to Learn and Use.
b. Creating Dynamic Web Applications Becomes Easier.
c. It provides reusable Components.
d. Maintains the consistency of data throughout all components. 
e. Highly flexible and simple to use.


QUESTION 4: What is the name of the Software Engineer that created React? Also, which company owns React?
ANSWER: React was created by Jordan Walke.
        React is owned by Meta (formerly Facebook) and a community of individual developers and companies.


QUESTION 5: What are the notable differences between HTML & JSX? Give at least 3 of them
ANSWERS:
a. YOU NEED TO RETURN A SINGLE PARENT ELEMENT IN JSX
         One of the major differences between HTML and JSX is that in JSX, you must return a single parent element, or it won't compile.

         A lot of developers use <div>...</div>, but a better one that many people use is “fragment”, <>...</> which makes the code more readable.

         In HTML, you are free to do whatever you want as you don’t have to return a single parent element.


b. YOU CAN IMPLEMENT JS DIRECTLY IN JSX
         In JSX, it is possible to write JavaScript directly. You can do this by putting the JavaScript in curly braces {...}. 
         Whereas in HTML, you need a script tag or an external JavaScript file to implement JavaScript


c. ALL TAGS SELF-CLOSE IN JSX
         Tags can self-close in JSX. That is, it is possible to have <div></div> as <div /> and <span></span> as <span />. You don't want to do that, but its possible.

         Self-closing tags in HTML can self-close without the slash before the right angle bracket, that is <br /> could work as <br>. But in JSX, you need to include the slash. This should bring something to mind – JSX heavily relies on HTML 4 syntax.


d. ClassName and HTMLFor, not class and for in JSX
         To define class names and for attributes in JSX, you don't do it as class or for, since both are reserved keywords in JavaScript.

         You actually create class components with the class keyword. So, to define class names in JSX, you do it as "className" and for attributes for labels you write "HTMLFor".


e. Write all HTML Attributes in camelCase in JSX
         You need to write all HTML attributes and event references in camelCase while writing JSX. So, onclick becomes onClick, onmouseover becomes onMouseOver, and so on.


f. Write Inline Styles as Objects in JSX
         And lastly, to define inline styles for JSX, you write it as an object, with the properties in camelCase, the values in quotes, and then you pass it inline to the JSX.

         This means you have to open up a style attribute and use curly braces instead of quotes. This is opposed to HTML where you're free to define millions of styles right inside the opening tag without writing them as objects and putting them in quotes.
         

QUESTION 6: Why can’t browsers read JSX?
ANSWER: Browsers cannot read JSX because there is no inherent implementation for the browser engines to read and understand them. 


















































































# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
