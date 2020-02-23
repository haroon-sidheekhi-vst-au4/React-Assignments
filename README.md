# React-Assignments


1. Create an app with create-react-app
2. Create both types of components - class, functional
3. How to create, maintain state inside a component
- - L1. Create a class component with an input, and a span, whatever you type in the input, should be printed in the span as soon as you type, using the state of the component.
- - L2. In the same component, instead of a span, now you have to render a list. Whatever you type in the input field and click on submit button ( submit button should be disabled if the input field is empty I.e not even one character in the input field ), should get saved inside a list in the state, and that list should be displayed in the component.
- - L3. Continuing with the above example, along with a simple text field for the todo input, you will have one more input of type date, from which you will select the day on which you have to do that task. Now above the list of todos that you’re rendering, you will have to add a select option button ( which is a dropdown ) in the component, which will show weekdays in the dropdown ( Monday, Tuesday … ), on selection of any of the days, you have to show all the tasks you created which fall on a Monday, or whatever day you selected from the dropdown
(L1,L2,L3 are levels in the problem)
4.  How to pass props from parent to child and vice versa
- - L1. Create a parent class component and a child class component, keep input inside child, a span in parent, whatever you type in child should be printed in the span in parent. Repeat this same exercise with a parent class component and child functional component.
- - L2. You store a list of usernames in the parent, send it down to child as props, show the list of users in a dropdown ( by default the first user is selected) next to the input field, now when you type a to do in the input field and press submit, you send the username and to do back to the parent, and display all the todos in a list.
- - L3. You create the L2 functionality, and then add a dropdown in the parent similar to the one in the child, with the list of users, on selection of a user, you show all todos for that person.
- - L4. In the general list of all todos, which will contain a mix of all todos for multiple users, for each user, you show his/her todos with a different background colour, for example John's todos will have blue background, Samantha's todos will have green background and so on.
5. How to connect to redux and start using it
- - L1. Set up redux, create a state, add some fields to it, create a reducer, create a store using the reducer, expose it to the react app, connect the app component to the store with the CONNECT function, display the fields you set in the redux state inside the react component
- - L2. Do the above, now inside the state, keep a field searchTerm, with some text as the value, this text is to be shown inside an input field which is inside app component in react, also, upon typing or deleting from the input field, the redux state searchTerm should change.
- - L3. Continuing from above, once you type something in the input field and press submit ( submit button disabled when the input is empty), you save the to-do data inside an array in redux state, and that list of todos should be rendered inside a list component, which is a child component of the App component.
- - L4. While creating the to do, you also save a date for the to do, In the app component, next to the input, there should be a dropdown with three options "today"/"previous"/"next", upon selection of which, you'll show todos for the present day, or all todos before today, or all todos after today.
- - L5. You fetch a list of todos from "jsonplaceholder.com/todos", save it in the redux state when the app is loaded the first time. While the todos request is happening, you show the text "Loading..." On the screen, once the request fulfills, you show the todos, if the request fails, you show a retry button on the screen, upon click of which, the request will again go and the "loading..." Text comes back.

How is it structured?
There are main topics which they need to understand, L1, L2... are levels of complexity of the practice exercises to practice those concepts, everyone should begin with level 1 of any topic and see how far can they go.
