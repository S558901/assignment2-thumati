# Sree Chetan Reddy Thumati
Previously I worked on a project called 'A user oriented behaviour based malware variant detection for Android
systems'. It hepled me to improve my technical abilities as well as logical thinking.

![me](/SHIVA0010.jpg)

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

> [Button not showing console log function](https://stackoverflow.com/questions/75299954/button-not-showing-console-log-function)

```css
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

> [Custom Checkboxes and Radio Buttons](https://css-tricks.com/snippets/css/custom-checkboxes-and-radio-buttons)