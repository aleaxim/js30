Day 1 | 04.04.22


1. [Relearning HTML Dom Events](https://www.w3schools.com/jsref/dom_obj_event.asp)

We use the keyboard event, keydown
keydown	- The event occurs when the user is pressing a key

More on KeyboardEvent here https://www.w3schools.com/jsref/obj_keyboardevent.asp


To get the keycode of keys [https://keycode.info/](https://keycode.info/)


2. [querySelector vs querySelectorAll](https://www.javascripttutorial.net/javascript-dom/javascript-queryselector/)

The querySelector() method returns the first element that matches a CSS selector.

When selecting for only the first match, use querySelector, else querySelectorAll()


3. attribute selector 
ex. audio['data-key=65']

But we will not use this in this challenge, since we don't want to a variable live in our event function


4. ES6 Template literals (Template Strings)

Template literals are literals delimited with backtick (`) characters

- [Ref 1](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Template_literals)
- [Ref 2](https://www.javascripttutorial.net/es6/javascript-template-literals/)


5. How to replay the audio without waiting for it to end

.play() on an audio element, doesn't play the audio again when it's already playing

a way to solve this is we rewind it to the start 


6. [classList](https://www.w3schools.com/jsref/prop_element_classlist.asp) 

addClass('');   // jQuery version 
classList.add('')'  // Vanilla JS 

Examples.
    key.classList.add('playing');
    key.classList.remove('playing');
    key.classList.toggle('playing');


7. [Transition end event](https://www.w3schools.com/jsref/event_transitionend.asp)

i'm not clicked but i was transitioned,,, 
The transitionend event occurs when a CSS transition has completed.

