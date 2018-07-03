# reactTypeScriptNotes

function(vars){ === (vars) => { ?
EXCEPT that when using an arrow function, 'this' is not reset. Useful when using setTimeout( () => {console.log(this)} ,1000ms) 

If you are returning a single value, you can remove the { } as in const items = array.map((color) => '<li>' + color + '<li>')
'<li>' + color + '<li>' = '<li>${color}<li>' ?

public means it returns html or is in a public method.. 

: void means it doesn't return anything
public render(): JSX.Element {

//in .tsx//var foo = bar as foo === var foo = <foo>bar //in .ts//  <foo> bar </foo> gives JSX

with object address, const {street: st, city, country} = address; gives variables the value address.x

...array is the full array or the full object; ...address

Class has constructor instead of initialize, then to make one is new Person('Mosh')

To do inheritance, use extends and then constructor has to have the variables from the parents as well as call super on the parent variables; constructor(name, degree){ super(name); this.degree = degree;}

modules is creating a new file for each object or method, need to have export before class and also have import {teacher} from "./teacher"; adding default will allow for exclusion of curly braces and node modules don't need ./


TYPESCRIPT

enum color {red = 0, blue = 1}

let message: any;
message = 'abc';
let myMessage = (message as string).endsWith("c");

$(document).ready(function(){  === $(function(){
