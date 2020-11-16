## :notebook_with_decorative_cover: Libft

#### :page_facing_up: Program name

- **`libft.a`**

#### :page_facing_up: Turn in files

- `*.c`, `libft.h`, `Makefile`

#### :page_facing_up: Description

- Write your own library, containing an extract of important functions for your cursus.
- You are free to add any function to your libft as you see fit.

#### :page_facing_up: Functions List

- Part 1 - Libc functions

  ```
  memset, bzero, memcpy, memccpy, memmove, memchr, memcmp,
  strlen, strlcpy, strlcat, strchr, strrchr, strnstr, strncmp,
  atoi, isalpha, isdigit, isalnum, isascii, isprint, toupper, tolower,
  calloc, strdup
  ```

- Part 2 - Additional functions (~100)

  ```
  substr, strjoin, strtrim, split, itoa, strmapi,
  putchar_fd, putstr_fd, putendl_fd, putnbr_fd
  ```

- Bonus Part (~115)

  ```
  lstnew, lstadd_front, lstsize, lstlast,
  lstadd_back, lstdelone, lstclear, lstiter, lstmap
  ```

- [My own functions](/02_myown)

  - [get_next_line](/02_myown/get_next_line.c)

    ```c
    int get_next_line(int fd, char **line);
    ```

    Write a function which returns a line read from a file descriptor, without the newline.

  - [isspace](/02_myown/ft_isspace.c)

    ```c
    int ft_isspace(int c);
    ```

    Checks for white-space characters. (`" "`, `\f`, `\n`, `\r`, `\t`, `\v`)

  - [chrdel](/02_myown/ft_chrdel.c)

    ```c
    char *ft_chrdel(char const *s, char c);
    ```

    Remove all specific characters(c) from a string(s).

------

#### :link: Test Tools Links

- [**Libftest** by jtoty](https://github.com/jtoty/Libftest)
- [**libft-unit-test** by alelievr](https://github.com/alelievr/libft-unit-test)
- [**libft-war-machine** by ska42](https://github.com/ska42/libft-war-machine)

