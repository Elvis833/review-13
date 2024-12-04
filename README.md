# Review 13

## 1

- This is an array: `[1, 2, 3]`. Map over it to create another array containing: `[2, 4, 6]`

```jsx
const array=[1, 2, 3].map(
  const arrey.map ()=> {2,4,6}
);
```

## 2

- This is a React component rendering a list of ice cream flavors. There are 6 bugs. Can you
  find and fix them?

```jsx
function IceCreamShowcase() => {
  const iceCreamFlavors =[
    "Rockmelon and Lime",
    "Cookies & Cream",
    "Strawberry Cookies & Cream",
    "Hokey Pokey", 
    "Vanilla",
    "Lime and Coconut",
  ];

  return (
    <div>
    <h1>Ice Cream!</h1>

    <ul>
    {iceCreamFlavors.map(() => {
      <li>flavor<li>
    })};
    </ul>
    </div>
  )
}
```

## 3

- Name something you took away from Dan Walker's chat this morning

His proud to be Maori
& Mana Wahine
