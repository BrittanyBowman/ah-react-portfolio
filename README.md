<img src="https://s3.amazonaws.com/devmountain/readme-logo.png" width="250" align="right">

# Project Summary

In this project we will be recreating the single page portfolio site we made but will be using React. This project will reinforce your knowledge of React and several topics including `components`, `state` and `props`

## Setup

* `fork` and `clone` this repository.
* `cd` into the project directory where you would like it to live.
  * Remember, this is why folder structure is important. We want our projects to be separate from each other.
* Run `create-react-app portfolio`.
  * This will create a new React app called `portfolio`

## Step 1

### Summary

In this step, we will set up the initial structure for our portfolio page. Think back to our HTML/CSS portfolio page and what we did to separate out each part. We set each section as it's own color block. In React, we want to create a new component for each section. Inside of `App.js` remove all of the code between the outermost div with a class of `App`. We will also want to remove that class from the div as well.

Next, Create a new folder inside of the `src` folder called `components`. This new folder will hold our components for the `Hero`, `About`, `Projects` and `Contact` sections. Go ahead and create four new files named after each of those sections. Remember:

* Components should follow a capitalized naming pattern for not only their file but the actual name itself.

The last thing we will need to do is import all of our newly created components into our `App.js` file.

### Instructions

* Open `src/App.js`.
* Remove all code from inside the outermost `div` with a class of `App`
  * Remove the class name as well
* Create a folder inside of `src` called `components`
  * Create a `Hero.js` file
    * Create a class based component called `Hero`
    * Export the component
  * Create a `About.js` file
    * Create a class based component called `About`
    * Export the component
  * Create a `Projects.js` file
    * Create a class based component called `Project`
    * Export the component
  * Create a `Contact.js` file
    * Create a class based component called `Contact`
    * Export the component
* Import our new components into the `App.js` component.

### Solution

<details>

<summary> <code> src/App.js </code> </summary>

```jsx
import React, { Component } from 'react';

// Components
import Hero from './components/Hero';
import About from './components/About';
import Projects from './components/Projects';
import Contact from './components/Contact';

class App extends Component {

  render() {
    return (
      <div>

      </div>
    )
  }
}

export default App;
```

</details>

<details>

<summary> <code> src/components/Hero.js </code> </summary>

```jsx
import React, { Component } from 'react';

class Hero extends Component {

  render() {
    return (
      <div>

      </div>
    )
  }
}

export default Hero;
```

</details>

<details>

<summary> <code> src/components/About.js </code> </summary>

```jsx
import React, { Component } from 'react';

class About extends Component {

  render() {
    return (
      <div>

      </div>
    )
  }
}

export default About;
```

</details>

<details>

<summary> <code> src/components/Projects.js </code> </summary>

```jsx
import React, { Component } from 'react';

class Projects extends Component {

  render() {
    return (
      <div>

      </div>
    )
  }
}

export default Projects;
```

</details>

<details>

<summary> <code> src/components/Contact.js </code> </summary>

```jsx
import React, { Component } from 'react';

class Contact extends Component {

  render() {
    return (
      <div>

      </div>
    )
  }
}

export default Contact;
```

</details>

## Step 2

### Summary

Now that we have created our components, we will want to actually render (use) them on the screen. We can do this by adding them as a child inside of our `App.js` component.

We render components by putting them inside of a tag, just like an HTML element, like this:

```jsx
<ComponentName />
// OR if we plan on putting children inside of that component
<ComponentName></ComponentName>
```

We will render each component inside of `App.js`. If you check out your browser, you will see nothing...how exciting. The reason for this is because we haven't given any styling to each of our components.

In React, we have a couple options for styling but we will stick with an external CSS file and import it at the top of our file, very simliar to how we would with HTML.

We will follow the exact same layout structure as our HTML/CSS portfolio page and even use the same classes for styling.

* Remember that React uses a slightly different syntax for styling classes, `className=""`. The reason for this is because `class` is a reserved word in JavaScript.

### Instructions

## Wrap Up

## Contributions

If you see a problem or a typo, please fork, make the necessary changes, and create a pull request so we can review your changes and merge them into the master repo and branch.

## Copyright

© DevMountain LLC, 2019. Unauthorized use and/or duplication of this material without express and written permission from DevMountain, LLC is strictly prohibited. Excerpts and links may be used, provided that full and clear credit is given to DevMountain with appropriate and specific direction to the original content.

<p align="center">
<img src="https://s3.amazonaws.com/devmountain/readme-logo.png" width="250">
</p>
