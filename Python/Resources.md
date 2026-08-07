
# Operators

|**Operator Type**|**Operators**|**Example**|**Result**|
|---|---|---|---|
|**Arithmetic**|`+`|`10 + 5`|`15`|
||`-`|`10 - 5`|`5`|
||`*`|`10 * 5`|`50`|
||`/`|`10 / 5`|`2.0`|
||`//`|`10 // 3`|`3` (Floor Division)|
||`%`|`10 % 3`|`1` (Remainder)|
||`**`|`2 ** 3`|`8` (Exponentiation)|
|**Comparison (Relational)**|`==`|`10 == 5`|`False`|
||`!=`|`10 != 5`|`True`|
||`>`|`10 > 5`|`True`|
||`<`|`10 < 5`|`False`|
||`>=`|`10 >= 5`|`True`|
||`<=`|`10 <= 5`|`False`|
|**Assignment**|`=`|`x = 10`|Assigns value|
||`+=`|`x += 5`|`x = x + 5`|
||`-=`|`x -= 5`|`x = x - 5`|
||`*=`|`x *= 5`|`x = x * 5`|
||`/=`|`x /= 5`|`x = x / 5`|
||`//=`|`x //= 5`|Floor divide and assign|
||`%=`|`x %= 5`|Modulus and assign|
||`**=`|`x **= 2`|Power and assign|
|**Logical**|`and`|`True and False`|`False`|
||`or`|`True or False`|`True`|
||`not`|`not True`|`False`|
|**Bitwise**|`&`|`5 & 3`|`1`|
||`\|`|`5 \| 3`|`7`|
||`^`|`5 ^ 3`|`6`|
||`~`|`~5`|`-6`|
||`<<`|`5 << 1`|`10`|
||`>>`|`5 >> 1`|`2`|
|**Membership**|`in`|`'a' in 'apple'`|`True`|
||`not in`|`'z' not in 'apple'`|`True`|
|**Identity**|`is`|`a is b`|`True` if both refer to the same object|
||`is not`|`a is not b`|`True` if they refer to different objects`|


## Patterns

```python
for i in range(0,5):
	print(i, end=" ");
```

```output
1 2 3 4 5
```


# Approach

```
*****
*****
*****
*****
*****
```

```python
for i in range(0,5):
	for j in range(0,5):
		print("*", end="")
	print()
```

|     | j=0 | j=1 | j=2 | j=3 | j=4 |
| --- | --- | --- | --- | --- | --- |
| i=0 | *   | *   | *   | *   | *   |
| i=1 | *   | *   | *   | *   | *   |
| i=2 | *   | *   | *   | *   | *   |
| i=3 | *   | *   | *   | *   | *   |
| i=4 | *   | *   | *   | *   | *   |

---

```
1
1 3
1 3 5 
1 3 5 7 
1 3 5 7 9
```


```
    *
   ***
  *****
 *******
*********
```


|     | j=1 | j=2 | j=3 | j=4 | j=5 | j=6 | j=7 | j=8 | j=9 |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
| i=1 |     |     |     |     | *   |     |     |     |     |
| i=2 |     |     |     | *   | *   | *   |     |     |     |
| i=3 |     |     | *   | *   | *   | *   | *   |     |     |
| i=4 |     | *   | *   | *   | *   | *   | *   | *   |     |
| i=5 | *   | *   | *   | *   | *   | *   | *   | *   | *   |


|     | j=1 | j=2 | j=3 | j=4 | j=5 |
| --- | --- | --- | --- | --- | --- |
| i=1 |     |     |     |     | *   |
| i=2 |     |     |     | *   | *   |
| i=3 |     |     | *   | *   | *   |
| i=4 |     | *   | *   | *   | *   |
| i=5 | *   | *   | *   | *   | *   |


![[Media/Diagram.svg]]
