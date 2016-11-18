# CSSPIN
CSS Spinners and Loaders - Modular, Customizable and Single HTML Element Code

## Installation
Install CSSPIN with **Bower** Package Manager     
`bower install csspin`

## Less File Structure 
`./less/
  ... _globals.less
  ... _round.less
  ... csspin-xxxx.less
  ... csspin.less
`

## How Less Stucture Works   
** Less files `with _` are partials and have actual magic  
** Less files `without _` only imports partials   
** Less files named `csspin-xxxx.less` imports `_globals.less` and respective `_partial.less`   
** Less files named `csspin-xxxx.less` acts as an individual module and can be compiled to `css/csspin-xxxx.css` for individual use   
** Less file named `csspin.less` imports all the partials and is compiled to `csspin.css`  

## CSS File Structure   
`./   
  ... csspin.css   
  ... css/csspin-xxxx.css   
`

## How CSS Stucture Works
** CSS File named `csspin.css` consists CSS for all the spinner
** CSS File named `csspin-xxxx` consists css of respective spinner

## Credits
Crafted with :heart: at [Webkul](http://webkul.com) HQ
