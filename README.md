# Libft

> **42 cursus** · C · the foundation library reused across every later project.

A custom C library re-implementing a selection of the standard C library functions, plus extra utilities for memory, strings, and linked lists.

## Features

- libc reimplementations: `ft_strlen`, `ft_memcpy`, `ft_strdup`, `ft_atoi`, `ft_split`…
- Additional utilities: `ft_putstr_fd`, `ft_itoa`, `ft_substr`…
- Singly linked list module: `ft_lstnew`, `ft_lstadd_back`, `ft_lstmap`…

## Build

```bash
make        # builds libft.a
make clean  # remove object files
make fclean # remove objects + library
make re     # rebuild
```

## Usage

```bash
# In your project
cc main.c -L. -lft -I. -o my_program
```

## Key concepts

Memory management, pointers, string manipulation and linked lists — the toolbox every 42 student carries forward.

---

*42 cursus project — [github.com/rjacquet31](https://github.com/rjacquet31)*

