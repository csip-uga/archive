---
title: "INSERT TITLE"
date: 2019-02-25
---

# TITLE

In the C library, there exists a useful function named **memcpy** which is used to copy a block of data from a source address to a destination address.

We declare it with the following function:
```
void *memcpy(void *str1, const void *str2, size_t n)
```
* str1 − This is pointer to the destination array where the content is to be copied, type-casted to a pointer of type void*.
* str2 − This is pointer to the source of data to be copied, type-casted to a pointer of type void*.
* n − This is the number of bytes to be copied.

We can see an example of the function in the character array below:
```
*s = pointer to source[0]
*d = pointer to destination[7]

memcopy(*s, *d, 3)

before:
char source[15] = | 'U' | 'G' | 'A' | ' ' | 'i' | 's' | ' ' | 't' | 'h' | 'e' | ' ' | 'b' | 'e' | 's' | 't' |

after:
char destination[15] = | 'U' | 'G' | 'A' | ' ' | 'i' | 's' | ' ' | 'U' | 'G' | 'A' | ' ' | 'b' | 'e' | 's' | 't' |
```
##

a function named memcopy() is used to move a block of data from a source address to a destination address. A similar fu