# React II

1. Conditional Rendering:  if (isLoggedIn) {  return <UserGreeting />;  }
  - Element Variable:  if (isLoggedIn) {      button = <LogoutButton onClick={this.handleLogoutClick} />;   } else {   button = <LoginButton onClick={this.handleLoginClick} />;  }
  - Inline If-Else with Conditional Operator: {isLoggedIn ? 'currently' : 'not'}
  - Preventing Component from Rendering: Return null
  
2. Lists and Keys: const numbers = [1, 2, 3, 4, 5];
  - numbers.map() to loop array elements
  - Render Multiple items: const listItems = numbers.map((number) => <li>{number}</li>);
  - <ListItem key={number.toString()} value={number} />
> Keys should be given to the elements inside the array to give the elements a stable identity.
> Keys Must Only Be Unique Among Siblings

3. Forms: 
  - form tag: houses the onsubmit
  - label tag
  - input tag
  - textarea tag: can use value property
  - select with option tags
  - input type=file : lets the user choose one or more files from their device storage to be uploaded to a server or manipulated by JavaScript via the File API.

