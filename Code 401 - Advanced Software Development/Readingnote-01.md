
[*HOME*](https://nassir1976.github.io/reading-notes/)
## Readnote-1


### Describe (in plain English) what Array.map() does

- The map() method in JavaScript creates an array by calling a specific function on each element present in the parent array. It is a non-mutating method. Generally map() method is used to iterate over an array and calling function on every element of array.

### Describe (in plain English) what Array.reduce() does

- Array reduce() is an inbuilt method that executes the reducer function on each item of the array resulting in single output value. The reduce() method reduces an array to a single value. The reduce() method executes the provided function for each value of the array (from left to right).
normal promis .then() syntax

            async function locationZomatoAPIcall (city){
            let results = await 
            let city = request.query.city
            superagent.get(HTTPS:developer.zomato.com/api/v2.1/location ? quary =${city});
            const locationData = data.body;
            console.log(locationData);
            result.body .geodata
           }
            getcity('seattle')

### with async/await syntax

            function locationZomatoAPIcall (city){
            let city = request.query.city
            superagent.get(HTTPS:developer.zomato.com/api/v2.1/location ? quary =${city});
            .then(geodata =>{
            conslole.log (locationData);
            result.body .geodata
           })
           }
         getCity('seattle')

### Explain promises as though you were mentoring a Code 301 level student

- JavaScript is single threaded, meaning that two bits of script cannot run at the same time; they have to run one after another. A Promise is an object that represents the eventual completion (or failure) of an asynchronous operation, and its resulting value. attribute:https://www.freecodecamp.org/news/javascript-promises-explained/ (Links to an external site.)

### Are all callback functions considered to be Asynchronous? Why or Why Not?

- Well, basically yes, but there's a catch. Every asynchronous function takes a function argument, but not every function that does so is asynchronous. It matters how the argument is used inside the function.
- Simply taking a callback doesn't make a function asynchronous. There are many examples of functions that take a function argument but are not asynchronous. For example there's forEach in Array. It iterates over each item and calls the function once per item.
