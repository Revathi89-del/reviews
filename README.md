The flow of the application is:

- Import the reviews data into your project as an array of objects.
- Set up the reviews data as a state variable using the useState hook.
- Render the first person's review in the list using their image, name, job, and text properties.
- Set up buttons to display the next and previous reviews in the list. Keep track of the current index in the reviews array and update it when the user clicks the next or previous button.
- Set up a button to display a random person's review. This button should select a random index in the reviews array and use it to display the corresponding person's review.

#### React Icons (Optional)

[Docs](https://react-icons.github.io/react-icons/)

```sh
npm install react-icons --save
```

```

#### Prev and Next

To allow the user to cycle through the reviews, you can set up buttons to display the next and previous reviews in the list. You can do this by keeping track of the current index in the reviews array, and updating the index when the user clicks the next or previous button. You can then use the updated index to access the corresponding person's review from the reviews array.

#### Random

To allow the user to display a random person's review, you can set up a button with functionality to randomly select an index in the reviews array. You can then use the selected index to display the corresponding person's review.

```
