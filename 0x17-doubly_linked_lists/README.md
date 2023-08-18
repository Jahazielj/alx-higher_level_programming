0x17. C - Doubly linked lists
0. Print list
 a function that prints all the elements of a dlistint_t list.
1. List length
 a function that returns the number of elements in a linked dlistint_t list.
2. Add node
 a function that adds a new node at the beginning of a dlistint_t list.
3. Add node at the end
a function that adds a new node at the end of a dlistint_t list.
4. Free list
a function that frees a dlistint_t list.
5. Get node at index
a function that returns the nth node of a dlistint_t linked list.
6. Sum list
a function that returns the sum of all the data (n) of a dlistint_t linked list.
7. Insert at index
a function that inserts a new node at a given position.
8. Delete at index
a function that deletes the node at index index of a dlistint_t linked list.
9. Crackme4
10. Palindromes

Prototype:
size_t print_dlistint(const dlistint_t *h);
size_t dlistint_len(const dlistint_t *h);
dlistint_t *add_dnodeint(dlistint_t **head, const int n);
dlistint_t *add_dnodeint_end(dlistint_t **head, const int n);
void free_dlistint(dlistint_t *head);
dlistint_t *get_dnodeint_at_index(dlistint_t *head, unsigned int index);
int sum_dlistint(dlistint_t *head);
dlistint_t *insert_dnodeint_at_index(dlistint_t **h, unsigned int idx, int n);
int delete_dnodeint_at_index(dlistint_t **head, unsigned int index);

