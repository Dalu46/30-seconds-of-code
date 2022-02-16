---
title: Getters
tags: objects,intermediate
firstSeen: 2022-06-16T17:31:08+01:00
---

Acts as methods and property.

- Use `get` to define a method on a class which can which is then accessed as a property.

```js
class Getters {
    constructor (name) {
        this.name = name;
    }
    get _name() {
        return this.name;
    }
}
let myName = new Getters('Joe');
```

```js
myName._name; // 'Joe'
```
