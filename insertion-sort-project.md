---

<a href="https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/insertion-sort-proje" target="_blank">Click here to view Question.</a>

---

### [22, 27, 16, 2, 18, 6] - [Insertion Sort]

---

### Stages of the above sequence according to the sort type;

- [**2**, 27, 16, **22**, 18, 6]

The number 22 at the beginning of the array and the number 2 in the middle of the array were replaced.

- [2, **6**, 16, 22, 18, **27**]

The number 27 at the beginning of the array and the number 6 in the end of the array were replaced.

- [2, 6, **16**, 22, 18, 27]

At this stage, it started from the 2nd value and compared, but since an value less than 16 was not in the continuation of the array, no displacement was applied.

- [2, 6, 16, **18**, **22**, 27]

The number 22 at the middle of the array and the number 18 in the end of the array were replaced.

- [2, 6, 16, 18, 22, 27]

Since the array is sorted at this stage, the processes are finished.

---

### Big-O notation;

- n! = n*(n+1)/2) = (n²+n)/2 => O(n²)

---

### Time Complexity;

- Best Case: O(n)
- Average Case: O(n²)
- Worst Case: O(n²)

---

### Which case must the value of array 18 be?

- The value 18 is in the average case because it is in the middle of the array.

---

### [7, 3, 5, 8, 2, 9, 4, 15, 6] - [Insertion Sort]

---

### 4 steps of the array according to the Insertion Sort;

- [**2**, 3, 5, 8, **7**, 9, 4, 15, 6]

The number 7 at the beginning of the array and the number 2 in the middle of the array were replaced.

- [2, **3**, 5, 8, 7, 9, 4, 15, 6]

No change was applied as there is no number that can replace the number 3 in the array.

- [2, 3, **4**, 8, 7, 9, **5**, 15, 6]

The number 5 at the beginning of the array and the number 4 in the end of the array were replaced.

- [2, 3, 4, **5**, 7, 9, **8**, 15, 6]

The number 8 at the beginning of the array and the number 5 in the end of the array were replaced.

---