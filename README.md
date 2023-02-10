# just-browser-os-things
- when you hide a scrollbar by CSS, you can't scroll on iOS and MacOS, not even using JS functions
- when password managers/browsers fill in a form input, it doesn't trigger any input events
- you have to explicitly reset input submit type styling on iOS using [`-webkit-appearance: none`](https://stackoverflow.com/a/5452829/15613610) 
- in CSS, [`height: 100vh`](https://css-tricks.com/css-fix-for-100vh-in-mobile-webkit/) doesn't expand when the search bar collapses 
- you have to explicitly remove borders on Safari version before 15.6 
- MacOS browsers ignore file input `accept` property for allowed file extensions
