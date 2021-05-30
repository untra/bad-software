# bad-software

This is a record of software defects and how they can be recognized:

## Bugs of Mutated State

### off-by-one errors
```java
public int <T>countElements(arr: Iterable<T>) {


}
```
### nested for-loops
### misuse of this
### time money entropy
### impure functions

## Bugs of Unstructured State

* TypeError
* IndexOutOfBounds (unless from off-by-one)
* DivideByZero

## Bugs of Shared State

* Race Conditions
* StackOverflows

