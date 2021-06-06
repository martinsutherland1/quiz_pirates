Question 1

Which component is responsible for requesting all the pirates?

PirateContainer

Question 2

Which hook do we use to carry out the requestAll() method and when does it get triggered?

useState. It is triggered when a request is made to /pirates

Question 3

The requestAll() method creates a new instance of Request in order to gain the functionality to carry out various forms of request. Where is the Request class?

The request class is created in the helpers folder request.js

Question 4

Which method are we using from the Request class here?

get

Question 5

The PirateList component is in charge of rendering a list of pirate components. What is the pirateNodes function returning?

This returns an array of the pirate objects

Question 1

In the browser, when we click on one of the pirates names in the pirate list, our app renders a PirateDetail component. PirateDetail is in charge of rendering the information for a single pirate. But where is it getting its props passed down from?

This is passed down from the main container, the identifies each pirate using their unique id

What is the purpose of this code in PirateDetail?

This code is there to ensure no undefined erros. If the pirate object is empty it will return a loading.. screen

Question 3

In PirateDetail, to delete a pirate, we have a button with a listener "onClick" which triggers a function called "handleDelete". The handleDelete function uses a function onDelete. Where is it receiving onDelete from?

onDelte is a method created in the main container and passed down to PirateDetail

Question 1

In PirateContainer, what does Promise.all return?

Promise all returns the pirate table from the database and assigns it to a varible 

Question 2

Ideally, we want our state to live at the top of our component chain, except in one other scenario. This is when our component contains a, what? 

A method that is assigning a value to the state

