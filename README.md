# About
Dynlang is dynamic static-typed interpreted programming language for everything.

# Syntax
Basic showcase:
```csharp
int modifyValues(int a, int b) {
   return [ ((250 * a) / b) + 1050, a % b + 100 - 20];
} 

main() {
   var arr = modifyValues(1000, 25);
   print(arr[0] + arr[1]);
} 
```
Showcase of type-casting and string interpolation:
```csharp
main() {
   int a = 1000;
   print(`Hello, Dynlang! ${(string)a}`);
} 
```
