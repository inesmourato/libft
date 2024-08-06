# Libft
My very first own library!

### Mandatory Part

The project's mandatory functions are related to the manipulation of characters, strings, numbers and memory, with a total of 34 functions.

##### Checks and manipulates characters:

| Function  | Description |
|:----------|-------------|
|ft_isalpha |Checks if the character is alphabetic.     |
|ft_isdigit |Checks if the character is a decimal digit.|
|ft_isalnum |Checks if the character is alphanumeric.   |
|ft_isascii |Checks if the character belongs to the ascci table.|
|ft_toupper |Converts characters from lower case to upper case. |
|ft_tolower |Converts characters from upper case to lower case. |

##### Manipulates strings:

| Function  | Description |
|:----------|-------------|
|ft_strlen |Find the length of the string.   |
|ft_strlcpy | Copies an n number of characters from the source string to the destination. |
|ft_strlcat | Concatenates an n number of characters from the source string to the destination.|
| ft_strchr| Finds the character in the string (first occurrence). |
| ft_strrchr |Finds the character in the string (last occurrence). |
| ft_strncmp | Compares the first n characters of a string.|
| ft_strnstr | Finds a substring in a string (size-bounded) |
|ft_substr	|Extracts a substring from a string.|
|ft_strjoin	|Concatenates two strings into a new one and allocates space for the new string.|
|ft_strtrim	|Trims the beginning and the end of the string with the specified characters. |
|ft_split	| Splits a string, with a specified character as delimiter, into an array of strings.|
|ft_strmapi	|Creates a new string by modifying the string with a specified function.|
|ft_striteri |	Iterates through a string, enabling character and index manipulation.|

##### Manipulates memory:

| Function  | Description |
|:----------|-------------|
| ft_calloc	| Dynamically allocates memory to n elements, all initialized to zero.|
|ft_memset	| Fills a contiguous block of memory with a specific value.|
|ft_bzero	|Erases the data in the n bytes of the memory and writes zeros.
|ft_memcpy|	Specifies the range of characters which could not exceed the size of the source memory.|
|ft_memmove |	Copies a block memory from one location to another.|
|ft_memchr	|Reads the bytes sequentially and stops as soon as a matching bytes is found. |
| ft_memcmp	| Compares two blocks of memory. |
| ft_strdup	| Duplicates a string. |

##### Manipulates numbers:

| Function  | Description |
|:----------|-------------|
|ft_atoi	|Converts the ASCII character to an integer.|
|ft_itoa	|Converts an integer to an ASCII character.|

##### Writes into a file descriptor:

| Function  | Description |
|:----------|-------------|
|ft_putchar_fd	| Outputs a character to the given file.|
|ft_putstr_fd	|Outputs a string to the given file.|
|ft_putendl_fd	|Outputs a string to given file with a newline.|
|ft_putnbr_fd	|Outputs an integer to the given file.|

### Bonus

Bonus functions are related to list manipulation.

| Function  | Description |
|:----------|-------------|
|ft_lstnew	|Creates a new list.|
|ft_lstadd_front	|Adds a new element at the beginning of the list.|
|ft_lstadd_back	|Adds a new element at the end of the list.|
|ft_lstsize	|Counts the elements of a list.|
|ft_lstlast	|Finds the last element of the list.|
|ft_lstdelone|	Deletes an element from the list.|
|ft_lstclear	|Deletes a sequence of elements of the list from a starting point.|
|ft_lstiter|	Applies a function to the content of all list elements.|
|ft_lstmap	|Applies a function to the content of all list elements into a new list.|
