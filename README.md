# Programming Exercise

Your task is to figure out how this code works.

* Come with a test input for the function.
* Trace the flow of the program with your test input **without running the code**, keeping track of all of the variables and transformations until you can determine the output.
* Keep coming up with new inputs until you're confident until you're confident that you know how the function works.
* Write a summary of what the function does.

```js
function (person, petName){
  for (dog in person.dogs){
    if (dog.name === petName){
      return dog
    }
  }
}
```

| Input | Output |
| ------------------- | --------- |
|   Shawn, Clyde      |   dog     | 
|   Allison, Clyde    |   dog     | 
|   Alexis, Binx      | undefined | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This program will take two inputs; a persons name and a pet's name. It then will reference an array known as "dogs" if the inputted pet name is equevelent to a value found in the dogs array under the "name" expression it will then return the value of "dog" if the name is not foubnd in the dog array, it will then be unnable to perform the return of "dog" and thus would be considered "undefined"</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
