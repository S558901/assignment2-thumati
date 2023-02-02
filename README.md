# Sree Chetan Reddy Thumati
###### My favorite team Sport is india Badminton
I like this badminton sport because if we play daily the body **function** gets better and players will be more **felxible** also this sport will improves your **concentration**.

---
## Badminton Team
My favorite sport is Badminton, the team of this sport is Hyderabad Warriors
1. PV Sindhu
2. Srikanth
3. Sania
- Chennai Superstars
- Mumbai Rockets
- Pune Panthers

If you want to know more about me, visit [here](/AboutMe.md)


---

# Trip Advisory 

The table name is Trip Advisory, it consists of three columns first column consists of country names,second column consists of reason to visit, third column consists of number of days.

|       **Country**    |    **Reason to visit**    |**No. of days** |
|----------------------|---------------------------|----------------|
| India                |   Visit some places       |       5        |
| USA                  |   To meet family members  |       6        |
| Canada               |   To meet family members  |       7        |
| Egypt                |   Visit some places       |       8        |

___

**Funny Quotes**

> Common sense is like deodorant. The people who need it most never use it. -_Anonymous_
>
> If an egg is broken by an outside force life ends, if an egg is broken by an inside force life begins. -_Abdul Kalam_

___

# Code Fencing

> Styling radio button

[Link to Stackoverflow](https://stackoverflow.com/questions/25590269/styling-radio-button)

CSS code
```
/*
  Hide the original radios and checkboxes
  (but still accessible)

  :not(#foo) > is a rule filter to block browsers
  that don't support that selector from
  applying rules they shouldn't

*/
li:not(#foo) > fieldset > div > span > input[type='radio'],
li:not(#foo) > fieldset > div > span > input[type='checkbox'] {
  /* Hide the input, but have it still be clickable */
  opacity: 0;

  float: left;
  width: 18px;
}


li:not(#foo) > fieldset > div > span > input[type='radio'] + label,
li:not(#foo) > fieldset > div > span > input[type='checkbox'] + label {
  margin: 0;
  clear: none;

  /* Left padding makes room for image */
  padding: 5px 0 4px 24px;

  /* Make look clickable because they are */
  cursor: pointer;

  background: url(off.png) left center no-repeat;
}

/* Change from unchecked to checked graphic */
li:not(#foo) > fieldset > div > span > input[type='radio']:checked + label {
  background-image: url(radio.png);
}
li:not(#foo) > fieldset > div > span > input[type='checkbox']:checked + label {
  background-image: url(check.png);
}
```

[Custom Checkboxes and Radio Buttons](https://css-tricks.com/snippets/css/custom-checkboxes-and-radio-buttons/)