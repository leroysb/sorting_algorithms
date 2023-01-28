# Sorting algorithms & Big O
![algo](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-low_level_programming/248/willy-wonka.png)

## Resources
* [Sorting algorithms](https://en.wikipedia.org/wiki/Sorting_algorithm)
* [Big O notation](https://stackoverflow.com/questions/487258/what-is-a-plain-english-explanation-of-big-o-notation)
* [Sorting algorithms animation](https://www.toptal.com/developers/sorting-algorithms)
* [15 sorting algorithms in 6 minutes](https://www.youtube.com/watch?v=kPRA0W1kECg)
* [CS50 Algorithms explanation in detail by David Malan](https://www.youtube.com/watch?v=yb0PY3LX2x8&t=2s)
* [All about sorting algorithms](https://www.geeksforgeeks.org/sorting-algorithms/)

## Tasks
### 0. Bubble sort
![Bubble sort](https://www.youtube.com/watch?v=lyZQPjUT5B4&embeds_euri=https%3A%2F%2Falxswe.com%2F&feature=emb_imp_woyt)

A function that sorts an array of integers in ascending order using the Bubble sort algorithm
* Prototype: `void bubble_sort(int *array, size_t size);`

Write in the file `0-O`, the big O notations of the time complexity of the Bubble sort algorithm, with 1 notation per line:
* in the best case
* in the average case
* in the worst case

File: [0-bubble_sort.c](./0-bubble_sort.c), [0-O](./0-O)

### 1. Insertion sort
![Insertion sort](https://www.youtube.com/watch?v=ROalU379l3U&embeds_euri=https%3A%2F%2Falxswe.com%2F&feature=emb_imp_woyt)

A function that sorts a doubly linked list of integers in ascending order using the Insertion sort algorithm
* Prototype: `void insertion_sort_list(listint_t **list);`

Write in the file `1-O`, the big O notations of the time complexity of the Insertion sort algorithm, with 1 notation per line:
* in the best case
* in the average case
* in the worst case

File: [1-insertion_sort_list.c](./1-insertion_sort_list.c), [1-O](./1-O)

### 2. Selection sort
![selection sort](https://www.youtube.com/watch?v=Ns4TPTC8whw&feature=emb_imp_woyt)

A function that sorts an array of integers in ascending order using the Selection sort algorithm
* Prototype: `void selection_sort(int *array, size_t size);`

Write in the file `2-O`, the big O notations of the time complexity of the Selection sort algorithm, with 1 notation per line:
* in the best case
* in the average case
* in the worst case

File: [2-selection_sort.c](./2-selection_sort.c), [2-O](./2-O)

### 3. Quick sort
![Quick sort](https://www.youtube.com/watch?v=ywWBy6J5gz8&embeds_euri=https%3A%2F%2Falxswe.com%2F&feature=emb_imp_woyt)

A function that sorts an array of integers in ascending order using the Quick sort algorithm
* Prototype: `void quick_sort(int *array, size_t size);`
* You must implement the Lomuto partition scheme.
* The pivot should always be the last element of the partition being sorted.

Write in the file `3-O`, the big O notations of the time complexity of the Quick sort algorithm, with 1 notation per line:
* in the best case
* in the average case
* in the worst case

File: [3-quick_sort.c](./3-quick_sort.c), [3-O](./3-O)

### 4. Shell sort -Knuth Sequence
Function that sorts an array of integers in ascending order using the [Shell sort](https://en.wikipedia.org/wiki/Shellsort) algorithm, using the `Knuth sequence`
* Prototype: `void shell_sort(int *array, size_t size);`
* You must use the following sequence of intervals (a.k.a the Knuth sequence):
** n+1 = n * 3 + 1
** 1, 4, 13, 40, 121, ...

File: [100-shell_sort.c](./100-shell_sort.c)

### 5. Cocktail shaker sort
Function that sorts a doubly linked list of integers in ascending order using the [Cocktail shaker](https://en.wikipedia.org/wiki/Cocktail_shaker_sort) sort algorithm
* Prototype: `void cocktail_sort_list(listint_t **list);`

FIle: [101-cocktail_sort_list.c](./101-cocktail_sort_list.c), [101-O](./101-O)

### 6. Counting sort
function that sorts an array of integers in ascending order using the [Counting sort](https://en.wikipedia.org/wiki/Counting_sort) algorithm
* Prototype: `void counting_sort(int *array, size_t size);`

File: [102-counting_sort.c](./102-counting_sort.c), [102-O](./102-O)

### 7. Merge sort
Function that sorts an array of integers in ascending order using the [Merge sort](https://en.wikipedia.org/wiki/Merge_sort) algorithm
* Prototype: `void merge_sort(int *array, size_t size);`
* You must implement the `top-down` merge sort algorithm
** When you divide an array into two sub-arrays, the size of the left array should always be <= the size of the right array. i.e. `{1, 2, 3, 4, 5}` -> `{1, 2}, {3, 4, 5}`
** Sort the left array before the right array

File: [103-merge_sort.c](./103-merge_sort.c), [103-O](./103-O)
