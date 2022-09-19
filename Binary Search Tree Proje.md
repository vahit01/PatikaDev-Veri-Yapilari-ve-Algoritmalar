[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
   / \
  2   4
```
**Step 1**
* Root is 7.
```
      7
```
**Step 2**
* 5 is smaller than 7. So its on the right side of the root.
```
      7
     / 
    5
```
**Step 3**
* 8 is greater than 7. So its on the left side of the root.
```
      7
     / \
    5   8
```
**Step 4**
* 9 is greater than 8 and 7. So its on the left of the 8.
```
      7
     / \
    5   8
         \
          9
```
**Step 5**
* 1 is smaller than 5 and 7. So its on the right side of the 5.
```
      7
     / \
    5   8
   /     \
  1       9
```
**Step 6**
* 6 is greater than 5. So its on the left side of the 5.
```
      7
     / \
    5   8
   / \   \
  1   6   9
```
**Step 7**
* 0 is smaller than 1. So its on the right side of the 1.
```
      7
     / \
    5   8
   / \   \
  1   6   9
 / 
0
```
**Step 8**
* 3 is greater than 1. So its on the left side of the 1.
```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
```
**Step 9**
* 2 is smaller than 3. So its on the right side of the 3.
```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
   /
  2
```
**Step 10** 
* 4 is greater than 3. So its on the left side of the 3.
```
      7
     / \
    5   8
   / \   \
  1   6   9
 / \
0   3
   / \
  2   4
```
