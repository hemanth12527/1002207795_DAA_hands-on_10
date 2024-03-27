# 1002207795_DAA_hands-on_10
Implement a hash table and upload your code to github:

Use the multiplication AND division method for your hash function
Note your code should be generic enough to allow for ANY hash function
For simplicity assume your keys are integers and the values (data) are integers
Use collision resolution by chaining
Use a doubly linked list and you must write your own (so for example you can't use "list" in C++)
You are only allowed to use C-style array's for this implementation (so for example no C++ vectors)
Your Hash table should grow and shrink
When it's full double the array size and re-hash everything
When it's becoming empty e.g. 1/4 empty, then half the size of the array and re-hash everything
