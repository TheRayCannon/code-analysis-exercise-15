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
|   (Shawn, Clyde) = { for (dog in Shawn.dogs)= true { if dog.name === Clyde) = true     |  { dog }    | 
|   (Allison, Korra) = { for (dog in Allison.dogs)= true { if dog.name === Korra) = true |  { dog }    | 
|   (Alexis, Binx) = { for (dog in Alexis.dogs)= true { if dog.name === Binx) = flase    | undefined   | 

<table>
  <tr>
    <th>What does this program do?</th>
    <td>This program will take two inputs; a persons name and a pet's name. It then will reference an object known as "dogs" if the inputted person is within the object of dogs, it will be considered "true" and move into the if function, which will attempt to find an eqaul value beteen the inputted petName to the dogs object of "dog.name". If there is a mtaching value the return will read "dog". If the name is not foubnd in the dogs object, it will then be unnable to perform the return of "dog" and thus would be considered "undefined". In our test, we use "Clyde" as a dog, and we will assume that Clyde is apart of the object we cannot be certain as ourt example does not allow us acces, for the purpposes of this proof we will suspend our disblelief that Clyde is not a dog. Binx however is a 
cat! Even if Alexis is a name found within the scope of "dogs" as sher is a dog owner, the name "Binx" wopuld not have an equevelent value; As there is no part of our prgram that refers to the object "cats", and therefore will not be able to retrive a value for "binx", thus will come back undifined.</td>
  </tr>
</table>

## Rubric

* Contains a plausible collection of test cases
* Outputs are accurately derived from inputs
* Summary is plausible
