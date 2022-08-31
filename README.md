# Verify Account UI

<p align="center">
  <img src="https://media2.giphy.com/media/pM3f8Gk4F7k4khLiAh/giphy.gif?cid=790b7611b811b7c244c0e5dee25bb137a1518cde44197c92&rid=giphy.gif&ct=g">
</p>

- Hacky Implementation
  - needs better ui implementation
  - needs better flow-through on type
  - not compatible with mobile devices

[**better `<input type="number">`**](https://danf.ca/blog/2013/09/19/input-type-number-and-ios-numeric-keypad/)

To make numpad appear for number fields

```html
<input
	type="number"
	min="0"
	inputmode="numeric"
	pattern="[0-9]*"
	title="Non-negative integral number"
/>
```
