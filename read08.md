## COMPARISON OPERATORS :

#### 1. Less than (<) — returns true if the value on the left is less than the value on the right, otherwise it returns false.
#### 2. Greater than (>) — returns true if the value on the left is greater than the value on the right, otherwise it returns false.
#### 3. Less than or equal to (<=) — returns true if the value on the left is less than or equal to the value on the right, otherwise it returns false.
#### 4. Greater than or equal to (>=) — returns true if the value on the left is greater than or equal to the value on the right, otherwise it returns false.
#### 5. Equal to (===) — returns true if the value on the left is equal to the value on the right, otherwise it returns false.
#### 6. Not equal to (!==) — returns true if the value on the left is not equal to the value on the right, otherwise it returns false.

## LOGICAL OPERATORS :

#### 1. & (and) — This operator will be truthy (act like true) if and only if the expressions on both sides of it are true.
#### 2. || (or) — This operator will be truthy if the expression on either side of it is true. Otherwise, it will be falsy (act like false).
#### 3. var isTrue = ('yellow' === 'green') && (4 >= 4);
#### 4. In the example above, we check if the string 'yellow' is equal to the string 'green' and (&&) if 4 is greater than or equal to 4. Let’s break this down into the two comparison expressions.
#### 5. The first expression is false, because the string 'yellow' is not the same (equal) as the string 'green'.
#### 6. The second expression is true, because the number 4 is greater than or equal to 4.
#### 7. The && operator requires that both expressions be true in order for the expression to be truthy. Because one expression is false and the other is true, the expression is falsy and evaluates to false.

## Loops: while and for :

### The “while” loop :

#### The while loop has the following syntax:

#### while (condition) {
####   // code
####   // so-called "loop body"
#### }
#### While the condition is truthy, the code from the loop body is executed.

### The “for” loop :

#### The for loop is more complex, but it’s also the most commonly used loop.

#### It looks like this:

#### for (begin; condition; step) {
####   // ... loop body ...
#### }

##### Parts of “for” loop :
	
        1. begin i = 0 Executes once upon entering the loop.
        2. condition i < 3 Checked before every loop iteration. If false, the loop stops.
        3. body	alert(i) Runs again and again while the condition is truthy.
        4. step	i++	Executes after the body on each iteration.