# MONTY


## Description

Monty 0.98 is a scripting language that is first compiled into Monty byte codes (Just like Python). It relies on a unique stack, with specific instructions to manipulate it. The goal of this project is to create an interpreter for Monty ByteCodes files.

***

## Installation

1. Clone the repository:
```console
git clone git@github.com:The-Malik-of-Codes/monty.git
```

## Usage
1. Enter at directory
```console
cd monty
```

2. Compile:
```console
gcc -Wall -Werror -Wextra -pedantic -std=c89 *.c -o monty
```

3. Execute:
```console
./monty file.m
//The file contains the bytcode instructions for example
cat -e 000.m
push 0$
push 1$
push 2$
  push 3$
                   pall    $
push 4$
    push 5    $
      push    6        $
pall$
```

## Functions

The functions used are:

|Name | Description | Return| File
|:--: | :-- | :--| :--|
|_f_add | adds the top two elements of the stack | No Return | add.c|
| addnode | add node to the head stack | No Return | addnode.c|
| f_div | divides the top two elements of the stack. | No Return | div.c|
| execute | executes the opcode | No Return | execute.c|
| free_stack | frees a doubly linked list | No Return | free_stack.c|
| main | monty code interpreter | 0 on success | main.c| 

### Examples

```console
┌─[the-engineer-coder@the-robot-maker]─[~/Documents/Programming/Programming Codes/alx/monty]
└──╼ $ ls
basics.c    general.c  main.h  memory.c   shell.c
builders.c  helper.c   hsh          README.md  test
```

### Authors
[The Malik of Codes](https://github.com/The-Malik-of-Codes)