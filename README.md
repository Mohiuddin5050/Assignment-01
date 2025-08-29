1.	getElementById, getElementsByClassName, and querySelector , querySelectorAll are DOM selection methods. But they work different.
•	getElementById : It is select a single element . That is id.
Ex...  const element=document.getElementById(‘card’)
•	getElementsByClassName:  It is select all element with class name. To access, run a loop.
Ex...  const elements=document.getElementByClassName(‘card’)
for(const element of elements){}
•	querySelector: It is select first element that match CSS selector.
Ex...  const elements=document. querySelector (‘.card’)
Ex...  const elements=document. querySelector (‘#card’)

•	querySelectorAll: It is select all element that match CSS selector. To access, run a loop “forEach”. 
•	Ex...  const elements=document. querySelectorAll (‘.card’)
elements.forEach((button){})


2.	create and insert a new element into the DOM
Create element
const div=document.createElement(“div”)

insert element:
appendChild, prepend,before , after  uses.
ex:  document.body.appendChild(“div”)
ex:  document.body.prepend(“div”)



3.	


