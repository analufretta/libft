# Libft

A personal implementation of standard C library functions, written from scratch as part of the 42 curriculum.  
This project builds a static library `libft.a` containing re-creations of common libc utilities and helper routines for later projects.

---

## 🧩 Contents

### Part 1 — Standard Functions
Reimplemented versions of libc functions operating on memory and strings:

ft_isalpha, ft_isdigit, ft_isalnum, ft_isascii, ft_isprint  
ft_strlen, ft_memset, ft_bzero, ft_memcpy, ft_memmove  
ft_strlcpy, ft_strlcat, ft_toupper, ft_tolower  
ft_strchr, ft_strrchr, ft_strncmp, ft_memchr, ft_memcmp  
ft_strnstr, ft_atoi, ft_calloc, ft_strdup

### Part 2 — Additional Functions
Custom utility functions for string and memory handling:

ft_substr, ft_strjoin, ft_strtrim, ft_split  
ft_itoa, ft_strmapi, ft_striteri  
ft_putchar_fd, ft_putstr_fd, ft_putendl_fd, ft_putnbr_fd

## ⚙️ Compilation

Build the library:

```bash
make
```

Clean object files:
```bash
make clean
```

Remove all:
```bash
make fclean
```

Remove all and rebuild:
```bah
make re
```



