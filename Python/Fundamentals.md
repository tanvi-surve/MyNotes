![[Pasted image 20260803194013.png|350]]



# Variable Naming 

| **Rule**                                                    | **Allowed?**              |
| ----------------------------------------------------------- | ------------------------- |
| Starts with a letter (`a-z`, `A-Z`)                         | ✅ Yes                     |
| Starts with an underscore (`_`)                             | ✅ Yes                     |
| Starts with a number                                        | ❌ No                      |
| Contains letters, digits, and underscores                   | ✅ Yes                     |
| Contains spaces                                             | ❌ No                      |
| Contains special characters (`@`, `#`, `$`, `%`, `!`, etc.) | ❌ No                      |
| Uses Python keywords (`if`, `for`, `class`, `def`, etc.)    | ❌ No                      |
| Variable names are case-sensitive (`age`, `Age`, `AGE`)     | ✅ Yes (all are different) |


# Operators

| **Operator Type**           | **Operators** | **Example**          | **Result**                                 |
| --------------------------- | ------------- | -------------------- | ------------------------------------------ |
| **Arithmetic**              | `+`           | `10 + 5`             | `15`                                       |
|                             | `-`           | `10 - 5`             | `5`                                        |
|                             | `*`           | `10 * 5`             | `50`                                       |
|                             | `/`           | `10 / 5`             | `2.0`                                      |
|                             | `//`          | `10 // 3`            | `3` (Floor Division)                       |
|                             | `%`           | `10 % 3`             | `1` (Remainder)                            |
|                             | `**`          | `2 ** 3`             | `8` (Exponentiation)                       |
| **Comparison (Relational)** | `==`          | `10 == 5`            | `False`                                    |
|                             | `!=`          | `10 != 5`            | `True`                                     |
|                             | `>`           | `10 > 5`             | `True`                                     |
|                             | `<`           | `10 < 5`             | `False`                                    |
|                             | `>=`          | `10 >= 5`            | `True`                                     |
|                             | `<=`          | `10 <= 5`            | `False`                                    |
| **Assignment**              | `=`           | `x = 10`             | Assigns value                              |
|                             | `+=`          | `x += 5`             | `x = x + 5`                                |
|                             | `-=`          | `x -= 5`             | `x = x - 5`                                |
|                             | `*=`          | `x *= 5`             | `x = x * 5`                                |
|                             | `/=`          | `x /= 5`             | `x = x / 5`                                |
|                             | `//=`         | `x //= 5`            | Floor divide and assign                    |
|                             | `%=`          | `x %= 5`             | Modulus and assign                         |
|                             | `**=`         | `x **= 2`            | Power and assign                           |
| **Logical**                 | `and`         | `True and False`     | `False`                                    |
|                             | `or`          | `True or False`      | `True`                                     |
|                             | `not`         | `not True`           | `False`                                    |
| **Bitwise**                 | `&`           | `5 & 3`              | `1`                                        |
|                             | `\|`          | `5 \| 3`             | `7`                                        |
|                             | `^`           | `5 ^ 3`              | `6`                                        |
|                             | `~`           | `~5`                 | `-6`                                       |
|                             | `<<`          | `5 << 1`             | `10`                                       |
|                             | `>>`          | `5 >> 1`             | `2`                                        |
| **Membership**              | `in`          | `'a' in 'apple'`     | `True`                                     |
|                             | `not in`      | `'z' not in 'apple'` | `True`                                     |
| **Identity**                | `is`          | `a is b`             | `True` if both refer to the same object    |
|                             | `is not`      | `a is not b`         | `True` if they refer to different objects` |
|                             |               |                      |                                            |