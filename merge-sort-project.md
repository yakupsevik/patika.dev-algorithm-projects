---

<a href="https://app.patika.dev/courses/veri-yapilari-ve-algoritmalar/merge-sort-proje" target="_blank">Click here to view Question.</a>

---

### [16, 21, 11, 8, 12, 22] - [Merge Sort]

---

### Stages of the above sequence according to the sort type;

- ```[16, 21, 11]    [8, 12, 22]```

Divide the array into two.

- ```[16]    [21, 11]    [8]    [12, 22]```

Divide the array into two.

- ```[16]   [[21] [11]]    [[8] [12]]   [22]```

Divide the array into two. And the splitting steps are complete. There are now binary and single values that can be arrayed.

- Final Step;

```
[16]  [11,21]  [8]  [12,22]
   \   /         \  /
 [11,16,21]     [8,12,22]
          \     /        
     [8,11,12,16,21,22]
```

The elements are started to merge again by arranging the binary parts within themselves.

---

### Big-O notation;

- n=6, O(n*(logn)) -> O(6*(log6))
- O(nlogn)

---