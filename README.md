# About
Dynlang is dynamic static-typed interpreted programming language for everything.

# Syntax
Basic showcase:
```csharp
int modifyValues(int a, int b) {
   return [ ((250 * a) / b) + 1050, a % b + 100 - 20 ];
} 

var arr = modifyValues(1000, 25);
print(arr[0] + arr[1]);
```
Showcase of type-casting and string interpolation:
```js
int a = 1000;
print(`Hello, Dynlang! ${a}`);
```
Showcase of object-oriented programming:
```csharp
class Car {
   public int price;
   ctor(int price) {
      this.price = price;
   } 
}


var car = new Car(1000);
print(car.price);
```
