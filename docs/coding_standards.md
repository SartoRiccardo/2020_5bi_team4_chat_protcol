# Coding Standards

This project will be programmed in Javascript (using React + Redux) and PHP.

## Javascript

### 1. Files

##### 1.1. File Naming

File names must follow the camelCase standard. If they contain a React component, they must start with a capital letter.

##### 1.2. File Structure

All React components must be in a folder called `components`. Redux states and action creators must be in a folder called `redux`. There may be multiple subfolders inside those two folders.

### 2. Formatting

##### 2.1. Braces

Curly braces must be used even if they are not necessary

```javascript
/* YES */
if(condition) {
  doSomething();
}

/* YES */
if(condition) {doSomething();}

/* NO */
if(condition) doSomething();
```

##### 2.2. Statements

There can only be one statement per line. Statements can only have whitespace characters behind them.

```javascript
/* YES */
if(condition) {
  doSomething();
}
else {
  doSomethingElse();
}

/* NO */
if (condition) {
  doSomething();
} else {
  doSomethingElse();
}
```

##### 2.3. Maximum line length

A single line may only have up to 120 characters, counting whitespaces.

##### 2.4. Line wrapping

It is heavily encouraged to only wrap lines at a higher syntactic level.

```javascript
/* YES */
const answer = (168 / 4)
		* 2;

/* NO */
const answer = (168
		/ 4) * 2;
```

### 3. React

##### 3.1. Destructuring props and state

Both props and state must be destructured before usage. If a key has the same name in both the props and the state, it cannot be destructured.

##### 3.2. Initializing the state

State must be initialized in the constructor.

##### 3.3. Prop passing

Props must be properly indented when passed in multiple lines.

```jsx
<MyComponent
	firstProp={firstValue}
	secondProp={secondValue}
	thirdProp={thirdValue}
/>
```

##### 3.4. JSX

JSX code must always be in parenthesis

##### 3.5 Dynamic JSX

Components passed dynamically must first be stored in a variable, and the variable can then be passed.

```jsx
const percentage = document.getElementById("percentage-input-field").value;

/* YES */
let body = null;
if(percentage > 100) {
  body = (
  	<p>That's not a valid value!</p>
  );
}
else {
  body = (
  	<React.Fragment>
    	<h1>You have typed {percentage}%</h1>
      <p>That's a pretty good percentage!</p>
    </React.Fragment>
  );
}

return (
	<div>
  	{body}
  </div>
);

/* NO */
return (
	<div>
  	{
      percentage > 100 ? (
        <p>That's not a valid value!</p>
      ) : (
        <React.Fragment>
          <h1>You have typed {percentage}%</h1>
          <p>That's a pretty good percentage!</p>
        </React.Fragment>
      )
    }
  </div>
);
```

