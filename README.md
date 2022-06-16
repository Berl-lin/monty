# Monty Project

###### 0x19. C - Stacks, Queues - LIFO, FIFO

---------------

## Resources

- [Google](https://www.google.com/search?q=stack+and+queue&sxsrf=ALiCzsYkWib2UHFE92xLbnBlEfVlyb8LGA%3A1655416759690&source=hp&ei=t6erYqquJuKqlQeB9a-QCA&iflsig=AJiK0e8AAAAAYqu1x5Bkm4UTyTcQA_nbPmg6ULh0IsLs&ved=0ahUKEwjq5ab_-7L4AhViVeUKHYH6C4IQ4dUDCAc&uact=5&oq=stack+and+queue&gs_lcp=Cgdnd3Mtd2l6EAMyBAgAEEMyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgAQyBQgAEIAEMgUIABCABDIFCAAQgARQAFgAYNMDaABwAHgAgAH4AYgB-AGSAQMyLTGYAQDAAQE&sclient=gws-wiz)
- [Stack Overflow](https://stackoverflow.com/questions/1433204/how-do-i-use-extern-to-share-variables-between-source-files)
- [Compilation & Output - stderr](https://github.com/sickill/stderred)

----------------

## General Requirements

- Allowed editors: vi, vim, emacs
- All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=c89
- All your files should end with a new line
- A README.md file, at the root of the folder of the project is mandatory
- Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
- You allowed to use a maximum of one global variable
- No more than 5 functions per file
- You are allowed to use the C standard library
- The prototypes of all your functions should be included in your header file called monty.h
- Don’t forget to push your header file
- All your header files should be include guarded
- You are expected to do the tasks in the order shown in the project

------------------

## The Monty Program

- Usage: monty file
	- where file is the path to the file containing Monty byte code
- If the user does not give any file or more than one argument to your program, print the error message USAGE: monty file, followed by a new line, and exit with the status EXIT_FAILURE
- If, for any reason, it’s not possible to open the file, print the error message Error: Can't open file <file>, followed by a new line, and exit with the status EXIT_FAILURE
	- where <file> is the name of the file
- If the file contains an invalid instruction, print the error message L<line_number>: unknown instruction <opcode>, followed by a new line, and exit with the status EXIT_FAILURE
	- where is the line number where the instruction appears.
	- Line numbers always start at 1
- The monty program runs the bytecodes line by line and stop if either:
	- it executed properly every line of the file
	- it finds an error in the file
	- an error occured
- If you can’t malloc anymore, print the error message Error: malloc failed, followed by a new line, and exit with status EXIT_FAILURE.
- You have to use malloc and free and are not allowed to use any other function from man malloc (realloc, calloc, …)

------------------

Solo by yours truly Christabell Owusu :grin: :see_no_evil: <br />
Please connect via [Twitter](https://twitter.com/berla_sterling) and/or [Github](https://github.com/Berl-lin). **THANK YOU!**

###### Let's make tea not love! :wink:

