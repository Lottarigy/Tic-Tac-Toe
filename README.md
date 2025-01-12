HELLO WORLD

```haskell
fn Main : Int32 -> Int32 =>
    >>Output : "Hello World\n"
    return 0
```

FUNCTIONS

```java
fn Main : Int32 -> Int32 =>
    
    let A -> Set = {2,3}
    let num1 -> Int16 = 18 
    let num2 -> Int16 = 22

    >>Output : >>Sum : A 
    >>Output : >>Diff : num1, num2

    return 0

fn Sum : Set -> Int32 => 
    return self[0 >- Set[0]] + self[0 >- Set[1]]

fn Diff : Int16, Int16 -> Int32 =>
    return self[0] + self[1]
```