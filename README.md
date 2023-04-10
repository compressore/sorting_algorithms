# Sorting Algorithms

Data Structures:
```
typedef enum kind_e
{
	SPADE = 0,
	HEART,
	CLUB,
	DIAMOND
} kind_t;
typedef struct card_s
{
	const char *value;
	const kind_t kind;
} card_t;
typedef struct deck_node_s
{
	const card_t *card;
	struct deck_node_s *prev;
	struct deck_node_s *next;
} deck_node_t;
```

## Tasks:

* **0. Bubble sort**

* **1. Insertion sort**

* **2. Selection sort**

* **3. Quick sort**

* **4. Shell sort - Knuth Sequence**

* **5. Cocktail shaker sort**

* **6. Counting sort**

* **7. Merge sort**

* **8. Heap sort**

* **9. Radix sort**

* **10. Bitonic sort**

* **11. Quick Sort - Hoare Partition scheme**

* **12. Dealer**
