# CSSPIN
CSS Spinners and Loaders - Modular, Customizable and Single HTML Element Code

## Demo
Check out [Spinners in Motion](https://webkul.github.io/csspin/)

## Installation
Install CSSPIN with **npm** or **Bower** Package Manager     
```
npm install csspin
```

```
bower install csspin
```

## Less File Structure 
```
./less/
  ... _globals.less   
  ... _round.less   
  ... csspin-xxxx.less   
  ... csspin.less   
```

## How Less Stucture Works?   
* Less files ```with _``` are partials and have actual magic  
* Less files ```without _``` only imports partials   
* Less files named ```csspin-xxxx.less``` imports ```_globals.less``` and respective ```_partial.less```   
* Less files named ```csspin-xxxx.less``` acts as an individual module and can be compiled to ```css/csspin-xxxx.css``` for individual use   
* Less file named ```csspin.less``` imports all the partials and is compiled to ```csspin.css```  

## CSS File Structure   
```
./css/    
  ... csspin-xxxx.css 
./csspin.css  
```

## How CSS Structure Works?   
* CSS File named ```csspin.css``` consists CSS of all the spinners
* CSS File named ```csspin-xxxx.css``` consists CSS of respective spinners

## Credits
Crafted with :heart: at [Webkul UXlab](http://design.webkul.com)
