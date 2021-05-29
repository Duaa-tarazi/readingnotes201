# TABLES
creating Tables in HTML

![](https://th.bing.com/th/id/R069e70f72d480b2dfcb33b78ba4d6401?rik=n1%2bPu9hFcLMcNQ&riu=http%3a%2f%2fwww.usna.edu%2fUsers%2fcs%2flmcdowel%2fcourses%2fsi204%2fS10%2flabs%2ftable_files%2fimage002.jpg&ehk=%2fyCq9ix5FuaD%2bDP4XOJaa6YiVTt2Fzao66I%2fGLWpm20%3d&risl=&pid=ImgRaw) </br>

* the syntax of ```<table>```tag ```<tr>```to start of each row ```<td>```each cell of the table represnting using td.

* ```<th>```to represent the heading of the table.
## TO spaning columns & TO spaning rows
 you can used on a ```<th>``` or ```<td>``` element and indicates how many columns or columns that cell should run across, using this properity ```colspan="value"```or ```rowspan="value"```.
> For long tables you can split the table into a ```<thead>```, 
```<tbody>```, and ```<tfoot>```.
# THE OBJECT 

what is the object : object is a collection of properties, and a property is an association between a name (or key) and a value. A property's value can be a function, in which case the property is known as a method.

simple code example of objects:

``` 
const student:{

name:'ahmad',

dateOfBirth:2000,

haight:180,

weight:75,

likes:['painting','reading']

walk :function(){statment...............}

talk:function(){statment....................}

}
```

## to access the object there is many ways:

*(student.name);

*let key ='likes';

(student[key]);

## to access an array in the object :

for(let i=0;i<student.likes.length;i++)

{console.log(student.likes[i];}

student.walk();

student.talk();

## to add new properity to object :

student.newprop='testing';

## to deleting properity:

delete student.dateofbirth;

 

 