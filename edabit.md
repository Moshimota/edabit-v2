[1.Classes For Fetching Information on a Sports Player](https://edabit.com/challenge/ZngT4zDckDugt2JGY)

Solution

```js
class Player {
	constructor(name, age, height, weight) {
		this.name = name
		this.age = age
		this.height = height
		this.weight = weight
	}
	
	getAge() {
		return this.name +" is age " + this.age
	}

	getHeight() {
		return this.name +" is "+ this.height +"cm"
	}
		
	getWeight() {
		return this.name +" weighs " + this.weight + "kg"
	}
}	
```

[2.Point Series 1: Skeleton](https://edabit.com/challenge/HwFtgwoW2qbQnoD6s)

Solution

```js
class Point {
	constructor(x, y){
		this.x = x;
		this.y = y;
	}
	toString(){
		return `[x=${this.x}, y=${this.y}]`;
	}
}
```

[3.Simple OOP Calculator](https://edabit.com/challenge/yxKoCKemzacK6PECM)

Solution

```js
class Calculator {
	add(a,b){return a+b};
	subtract(a,b){return a-b};
	multiply(a,b){return a*b};
	divide(a,b){return a/b};	
}
```

[4.Fullname and Email](https://edabit.com/challenge/kGLhgwGaLJsCMS7wS)

Solution

```js
class Employee {
	constructor (firstname, lastname) {
		this.firstname = firstname;
		this.lastname = lastname;
		this.fullname = `${firstname} ${lastname}`;
		this.email = `${firstname}.${lastname}@company.com`.toLowerCase();
	}
}
```