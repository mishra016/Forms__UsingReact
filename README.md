# Forms__UsingReact
##CHALLENGE: Make the code in App.jsx work.
The final app should have a single contact
with fName, lName and email.

HINT: You'll need to apply the following things you learnt:
1. Using JS Objects with state.
2. Making use of previous state when changing state.
3. Working with forms in React.
4. Handing events

 (when we are not using SpreadOperators use belkow written code)
 if (name === "fName") {
   return {
     fName: value,
     lName: prevValue.lName,
     email: prevValue.email
   };
 } else if (name === "lName") {
   return {
     fName: prevValue.fName,
     lName: value,
     email: prevValue.email
   };
 } else if (name === "email") {
   return {
     fName: prevValue.fName,
     lName: prevValue.lName,
     email: value
   };
Created with CodeSandbox
