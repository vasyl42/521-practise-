1/https://www.codewars.com/kata/find-the-smallest-integer-in-the-array/train/javascript?fbclid=IwAR0GAP90jhHfJFvVamQgDfJ0fuOa8wWUzOi76L1AMCiWnOnGWC_0Gx-1y_0
class SmallestIntegerFinder {
  findSmallestInt(args) {
  var temp  ;
 
    for (var i=0;i<args.length;i++){
        if(args[i]<=args[0]){
            args[0]  = args[i];    
            temp = args[i];
        }
      }
    return temp;
  }
 2/https://www.codewars.com/kata/find-the-smallest-integer-in-the-array/train/javascript?fbclid=IwAR0GAP90jhHfJFvVamQgDfJ0fuOa8wWUzOi76L1AMCiWnOnGWC_0Gx-1y_0
 function circleCircumference(circle) {
var circumference = (circle.radius *2*Math.PI)
return circumference
}

3/https://www.codewars.com/kata/fun-with-es6-classes-number-2-animals-and-inheritance/train/javascript?fbclid=IwAR0TNUP01YhF_AbjkGcjTdIKxxIRGrpj0fjhEZ4FTzPcrR9cevPHTWN2Tms
Animal = (function() {
  Animal = function(name, age, legs, species, status) {
    this.name = name;
    this.age = age;
    this.legs = legs;
    this.species = species;
    this.status = status;
  }

  Animal.prototype.introduce = function() {
    return 'Hello my name is ' + this.name + ' and I am ' + this.age + ' years old.';
  }
  return Animal;
})();

function Shark(name, age, status) {
  Animal.call(this, name, age, 0, 'shark', status);
}

Shark.prototype = Object.create(Animal.prototype);
Shark.prototype.constructor = Shark;


function Cat(name, age, status) {
  Animal.call(this, name, age, 4, 'cat', status);

  let catIntroduse = this.introduce;
  this.introduce = function() {
    return catIntroduse.call(this) + '  Meow meow!';
  }
}

Cat.prototype = Object.create(Animal.prototype);
Cat.prototype.constructor = Cat;

function Dog(name, age, status, master) {
  Animal.call(this, name, age, 4, 'dog', status);
  this.master = master;
}

Dog.prototype = Object.create(Animal.prototype);
Dog.prototype.constructor = Dog;

Dog.prototype.greetMaster = function() {
  return 'Hello ' + this.master;
}


class Animal {
  constructor(name, age, legs, species, status) {
    this.name = name;
    this.age = age;
    this.legs = legs;
    this.species = species;
    this.status = status;
  }
  introduce() {
    return `Hello, my name is ${this.name} and I am ${this.age} years old.`;
  }
}

class Shark extends Animal {
constructor(name, age, status) {
super(name, age, 0, "shark", status);
}
}

class Cat extends Animal {
constructor(name, age, status) {
super(name, age, 4, "cat", status);
}
introduce() {
return ${super.introduce()} Meow meow!;
}
}

class Dog extends Animal {
constructor(name, age, status, master) {
super(name, age, 4, "dog", status);
this.master = master;
}
greetMaster() {
return Hello ${this.master};
}
}


4/https://www.codewars.com/kata/training-js-number-12-loop-statement-for-dot-in-and-for-dot-of/train/javascript
const giveMeFive = object => {
  const result = []

  for (const key in object) {
    if (object.hasOwnProperty(key)) {
      if (key.length === 5) result.push(key)
      if (object[key].length === 5) result.push(object[key])
    }
  }

  return result
}

5/https://www.codewars.com/kata/understanding-closures-the-basics/train/javascript?fbclid=IwAR2OMDqLaR8wm2MH3ZAisspnO48sWsy6gQqQR1prA-n5jq-oVmAO9gS9MCo
function buildFun(n){

	var res = []

	for (let i = 0; i< n; i++){
		res.push(function(){
			return i
		})
	}
	return res
}
