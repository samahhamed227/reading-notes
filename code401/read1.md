# Node Ecosystem, TDD, CI/CD

1.  Describe (in plain English) what Array.map() does

- It is an array method that is used to iterate over an array and that is used to returns a new array and elements of the original arrays are result of callback function.
  - return new array
  - need a return 
  - This method accepts two parameters 

2.  Describe (in plain English) what Array.reduce() does 

- It is an array method that is executes a reducer function for each value of an array.
   - does not change the original array.
   - returns a single value which is the function's accumulated result.
   - need a return 
   
  3. Provide code snippets showing how to use superagent() to fetch data from a URL and log the result
   ### ***superagent()***

- With normal Promise `.then()` syntax:
`superagent.post('/api/pet').then(console.log).catch(console.error);`


- With `async / await` syntax:

` (async () => {
  try {
    const res = await superagent.post('/api/pet');
    console.log(res);
  } catch (err) {
    console.error(err);
  }
})(); `
4. Explain promises as though you were mentoring a Code 301 level student

The Promise object works as proxy for a value not necessarily known when the promise is created

Each promise has state, which can have one of the following values:
* Pending
* Fullfilled with a value
* Rejected for a reason

5. wrapping the asynchronous operation result
* No, not always callback functions considered to be Asynchronous, Every asynchronous function takes a function argument, but not every function that does so is asynchronous.

* For a function to be asynchronous it needs to perform an asynchronous operation. It needs to incorporate the argument callback in handling the results of this asynchronous operation. Only this way the function becomes asynchronous.