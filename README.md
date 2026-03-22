# Password Generator App

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

This solution provides a password, which is generated based on the selected inclusion options. The generated password can be copied with mouse Click or keyboard Tab-Enter.

User needs to choose the character length of password from the given slider.
They can choose from 1 to 30 characters long password.

User also has 4 provided checkbox options for password - 
	i). include Uppercase Letters
	ii). include Lowercase Letters
	iii). include Numbers
	iv). Include Symbols

They can choose one or more options for password. User needs to choose at least one option to be able to generate password.

If user chooses less password character length than chosen checkbox options, then password will not be generated.

They have to at least choose the same character length for password as their chosen checkbox options for the password to get generated.

For example, if they choose password length as `3` from the slider, and choose all of the 4 checkbox options, then password will not be generated. Only if they choose `4` or more password character length and choose all of the 4 checkbox options, then the password will get generated.

After user chooses the pasword character length slider and their checkbox choices, they can generate password by clicking or entering the `GENERATE` button.

After a new password is generated, it will also show the password strength.

There are 4 types of password strength - 

	a). `TOO WEAK!`
	b). `WEAK`
	c). `MEDIUM`
	d). `STRONG`

This is provided in `STRENGTH` box with various colors to indicate the password strength.

If user is satisfied with the generated password, they can copy the password for later use by clicking on or tabbing-entering on the copy icon, which can be found at the right side of the generated password.

After user copies the generated password, they will see `COPIED` text beside the copy icon.


### Screenshot

![Password-Generator-App.jpg](https://i.postimg.cc/3rLvtQw2/Password-Generator-App.jpg)


### Links

- Live Site URL: [Password Generator App](https://wandererfakeer.github.io/password-generator-app/)


## My process

### Built with

- Semantic HTML5 markup
- Accessible markup
- CSS custom properties
- CSS Flexbox
- CSS Grid
- JavaScript Event listener

## Author

- Sayani Mondal (Wanderer) - [@WandererFakeer](https://www.frontendmentor.io/profile/WandererFakeer)
