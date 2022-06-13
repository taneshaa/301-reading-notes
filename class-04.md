What is a ‘Controlled Component’? a component that renders form elements and controls them by keeping the form data in the component's state<br>
Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why. <br>
How do we target what the user is entering if we have an event handler on an input field? event handler will use setState to event.target.value<br>


Why would we use a ternary operator? To write shorter code <br>
Rewrite the following statement using a ternary statement:

if(x===y){
  console.log(true);
} else {
  console.log(false);
}
const truth = x === y ? 'true' : 'false';
