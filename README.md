# Kashmir Dairy

Website for Kashmir Dairy, a family dairy farm in Muzaffarabad, Azad Kashmir. Pure cow milk with home delivery.

## How to change the phone number or price

Open `index.html` and find the part near the bottom that starts with `const FARM = {`:

```js
const FARM = {
  phoneDisplay: "0300-0000000",   // how the number looks on the page
  whatsapp:     "923000000000",   // same number: 92 + number without the first 0, no dashes
  price:        "280"             // price per litre
};
```

Change the values inside the quotes, then save (on GitHub: press "Commit changes").
