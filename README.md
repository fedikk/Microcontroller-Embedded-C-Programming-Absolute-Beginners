# Microcontroller-Embedded-C-Programming-Absolute-Beginners

# Section 12 : taking input from user 

## Scanf()

```c
int age;
printf("Enter your age:");
scanf("%d",&age);
```
> Note
> you must add **&** before the variable

## getchar()

if you want to read a single char from the keyboard in ASCII form just use **getchar()**

```c
int a = getchar();
```

# Bit extraction 

if we want to extract a a portion of data 

1. shift the identification portion to right hand side until it touches the least significant bit
   a. Shift by the first index in our case we cant the portion [9::14] then data= data >> 9
3. Mask the value to extract only 6bits and save it into another variable


```c



```
