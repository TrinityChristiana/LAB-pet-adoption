## Requirements - Loops

- As a user, I want to see a listing of all available pets. Each pet should have a card that has all this data:
```javascript
{
  "image": xxx
  "name": xxx
  "color": xxx
  "specialSkill": xxx
  "typeOfPet": xxx
}
```

## Requirement - Part 1: HTML Representation of Data
- Create an array of at least 5 objects with data as shown above
- Loop through each object and print each item to the DOM

![MockUp1](MockUp1.png)


## Requirement - Part 2: Event Listeners

- As a user, I want to see 3 category(type) buttons printed at the top of the page. Each should be a different color. These can be hard-coded.
- I want to be able to click one of the 3 buttons, then only the cards that are in the category(type) should show.
- There should be some way for the user to unfilter the results (ie All Pets button).

![MockUp](MockUp.png)

## Requirement - Part 3: Create and Delete Pets
- Create a form that allows a user to add pets with a submit button
- When the submit button is pressed, the pet is added to the array and the DOM rerenders adding the new pet on the DOM.
- Each card should have a delete button that when clicked removes the pet from the array and re-renders the DOM
