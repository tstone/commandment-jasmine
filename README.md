## Overview ##

Commandment jasmine is an add-on for jasmine BDD testing which turns your behavior specs into CDD commandment driven development.

## Installation ##

Include commandment-jasmine.js after your jasmine.js file.

## Usage ##

```javascript
commandmentsFor("behavior", function(){
  thou("shalt be true", function(){
    expect(true).toBeTruthy();
  })
})
```
