# Libft - @42Born2Code
My first project in the 42 main core.

### TOC
* [What is libft?](#what-is-libft)
* [What's in it?](#whats-in-it)
* [How does it work?](#how-does-it-work)

### What is libft?
Libft is an individual project at 42 that requires us to re-create some standard C library functions that can be used later to build a library of useful functions for the rest of the program.

Disclaimer: *Reinventing the wheel is bad, 42 makes us do this just so we can have a deeper understanding of data structures and basic algorithms. At 42 we're not allowed to use some standard libraries on our projects, so we have to keep growing this library with our own functions as we go farther in the program.*

### What's in it?

As you can see from the [Project instructions][1], there are 4 sections:

1.  **Libc Functions:** Some of the standard C functions
2.  **Additional functions:** Functions 42 deems will be useful for later projects
3.  **Bonus Functions:** Functions 42 deems will be useful for linked list manipulation

Libc functions | Additional functions | Bonus Functions
:----------- | :-----------: | :-----------:
memset		| ft_memalloc	| ft_lstnew		
bzero		| ft_memdel		| ft_lstdelone	 
memcpy		| ft_strnew		| ft_lstdel		    
memccpy		| ft_strdel		| ft_lstadd		    
memmove		| ft_strclr		| ft_lstiter	    
memchr		| ft_striter	| ft_lstmap		
memcmp		| ft_striteri	|				
strlen		| ft_strmap		|				
strdup		| ft_strmapi	|				
strcpy		| ft_strequ		|				
strncpy		| ft_strnequ	|			
strcat		| ft_strsub		| 
strlcat		| ft_strjoin	| 
strchr		| ft_strtrim	| 
strrchr		| ft_strsplit	| 
strstr		| ft_itoa		| | 
strnstr		| ft_putchar	| 
strcmp		| ft_putstr		| 
strncmp		| ft_putendl	| 
atoi		| ft_putnbr		| | 
isalpha		| ft_putchar_fd	| |
isdigit		| ft_putstr_fd	| | 
isalnum		| ft_putendl_fd	| | 
isascii		| ft_putnbr_fd	| | 
isprint		|| 
tolower		| |

### How does it work?

The goal is to create a library called libft.a from the source files so I can later use that library from other projects at 42.

You should see a *libft.a* file and some object files (.o).


Now to clean up (removing the .o files and the .c files from the root), call `make clean`

**WARNING:** `make clean` will delete all your files from your root directory. Do not run it if you're using the `Makefile` file. This is why I added the `Makefile-sample` file.
