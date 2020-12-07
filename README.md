#  **Task 4**

## **Description :** 

* A Simple calculator in C language.

----

## **PseudoCode :**

* _Declaring two floating points to store the number and a char to store the operation needed._
* _Asking the user to input the first number and store it in first floating point._
* _Asking the user to define the operation._
* _Asking the user to input the second number and storing it in second floating point._
* _Finally printing the result and ending the program._


----


### **Actual Program :**

```c
#include<stdio.h>
#include<conio.h>

void main(){
     float n1,n2;
     char act;
     float result;
     printf("\n ----> Simple Calculator <----");
     printf("\n Enter the First Number : ");
     scanf("%f",&n1);
     printf("\n Enter the Operation : ");
     scanf(" %c",&act);
     printf("\n Enter the Second Number : ");
     scanf("%f",&n2);

     switch(act){
           case '+' : result = n1+n2;
           printf("\n Addition value = %f ",result );
           break;

           case '-' : result = n1-n2;
           printf("\n Subtraction value = %f ",result );
           break;

           case '*' : result = n1*n2;
           printf("\n Multiplication value = %f ",result );
           break;

           case '/' : result = n1/n2;
           printf("\n Division value = %f ",result );
           break;

     }
getchar();
}

```

----

## **Legend for the Calculator :**

| Operator | Operation |
|-------|---------------|
| + | Addition |
| - | Subtraction |
| * | Multiplication |
| / | Division |

---

### **Screenshots :**

![ScreenShot1](https://raw.githubusercontent.com/Siva50005/Cognizance2020/main/P1.JPG)

---

![ScreenShot2](https://raw.githubusercontent.com/Siva50005/Cognizance2020/main/P2.JPG)

---

![ScreenShot3](https://raw.githubusercontent.com/Siva50005/Cognizance2020/main/P3.JPG)

---

![ScreenShot4](https://raw.githubusercontent.com/Siva50005/Cognizance2020/main/P4.JPG)

---

**To-Do-List :**

* [x]Add one of the coolest project (or) program you have worked on with proper documentation(README) in the repository you created for task-3.
* [x]There should be atleast 5 commits in the repository at the time of submission.
* [x]Try to include images, bullet point, lists, tables, blockquotes, etc… in your README.md
* [ ]Marks for this task depends on your creativity.