# Template reference 

Also known as Local references.
Simply put, i need to grab an element in the component's template.
Note: What we are grabbing is the reference of the element itself. 

All we need is to put a template ref using a "hash"

```js
<input
  #userEmailRef // 👈 this is a template ref
  placeholder="user@email.com"/>
```


### Getting access to template ref in code 

We have another way to grab template refs in class file programmatically.

