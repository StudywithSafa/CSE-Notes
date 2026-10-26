C Programming - Important Programs with Viva

For CSE Students - Simple and Clear - By StudywithSafa

Program 1: Swap Two Numbers using Pointers

Code:

#include<stdio.h>void swap(int *a, int *b) { int temp; temp = *a; *a = *b; *b = temp;}int main() { int x=10, y=20; printf("Before: x=%d y=%d\n", x, y); swap(&x, &y); printf("After: x=%d y=%d", x, y); return 0;}

Output:

Before: x=10 y=20After: x=20 y=10

Viva Question: *a என்றால் என்ன? &x என்றால் என்ன?
Answer: *a = pointer 'a' point பண்ற address-ஓட value. &x = variable x-ஓட address.

Program 2: Print Array Elements using Pointers

Code:

#include<stdio.h>int main() { int arr[5]={10,20,30,40,50}, i; int *p; p = arr; printf("Array elements: "); for(i=0; i<5; i++) { printf("%d ", *(p+i)); } return 0;}

Output:

Array elements: 10 20 30 40 50

Viva Question: arr name என்ன கொடுக்கும்?
Answer: Array-ஓட first element-ஓட base address கொடுக்கும்.

Program 3: Structure to Store Student Details

Code:

#include<stdio.h>struct Student { char name[20]; int roll; float mark;};int main() { struct Student s1 = {"Safana", 101, 95.5}; printf("Name: %s\n", s1.name); printf("Roll: %d\n", s1.roll); printf("Mark: %.1f", s1.mark); return 0;}

Output:

Name: SafanaRoll: 101Mark: 95.5

Viva Question: Structure என்றால் என்ன?
Answer: Different datatype variables-ஐ ஒரே name-ல group பண்ணி வைக்கிற user-defined datatype.

