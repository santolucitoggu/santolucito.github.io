---
layout: default
title: CS102
---

# CS102 - Object Oriented Programming


## 3/21

Download [DrJava](http://www.drjava.org/) and start the program.
To run a program with DrJava, first click "Compile", then click "Run".
To make sure DrJava was installed correctly, copy and paste the following program.
When you save the program the name must match the first line.
So save this program as **CoinFlip.java**.

```java
public class CoinFlip {

  public static void main(String[] args) {
    // Math.random() returns a value between 0.0 and 1.0
    // so it is heads or tails 50% of the time
    if (Math.random() < 0.5) {
      System.out.println("Heads");
    }
    else {
      System.out.println("Tails");          
    }
  }
}
```
### Loops

Next we will try out a *while loop*.

```java
public class CountdownWhile {

  public static void main(String[] args) {
    int i = 10
    while (i >= 0) {
        System.out.println(i);
        i = i-1;
    }
  }
}
```

Practice it yourself
- Edit the program above (CountdownWhile) so that it counts up from 7 to 99.
- Write a while loop that will print the numbers 2,4,8,16,32,.. until you reach 100000

There are other ways to write a loop in java too!
This does the same as CountdownWhile, but look different.

```java
public class CountdownFor {

  public static void main(String[] args) {
    for (int i=0;i >= 0;i=i-1) {
        System.out.println(i);
    }
  }
}
```

Practice it yourself
- Write a for loop that counts up from 7 to 99
- Write a for loop that will print the numbers 2,4,8,16,32,.. until you reach 100000

## 3/16

We reviewed *if statements*.


## Week 1-2

#### Do this now
Download the [Syllabus](/ggu/CS102.pdf).

We will use [codecademy.com](https://www.codecademy.com), please create an account.
After you create an account, please take this [survey](http://goo.gl/forms/ML0lixndSJ), where you will be asked to input your username from codecademy.com.

#### Do this later

In your free time, [install python](https://www.python.org/downloads/) on your local computer.
This is not required right now, but will be needed later in the semester.

Join [Github](https://github.com/join) - this is like Linkedin for computer programmers.


#### Discrete Math

Here are some fun problems

### Room Key
You want to break into your friend's dorm room, but you don't know the keypad number.
The key is 4 numbers long, of number between 0-9, and it takes you 5 seconds to enter a 4 digit key.
How many hours do you need to break into your friend's room?

### Evens
Prove or disprove : the sum of two even numbers is even.

Prove or disprove : the product of two odd numbers is odd.

### 두끼
두끼 is a make-your-own ddeokbokki restaurant. You can choose from 4 sauces, 5 kinds of ddeok, and 6 vegetables.

If you can pick exactly one sauce, one ddeok, and one vegetable, how many different kinds of ddeokbokki can you make?

If you can pick only one sauce, pick 3 duk, and as many vegetables as you want, how many different kinds of ddeokbokki can you make?

### Knights and Knaves

 You visit an island has two kinds of inhabitants: knights, who always tell the truth, and knaves, who always lie. You meet two inhabitants, named A and B. They make the following statements:

A: We are both knights.

B: No, we aren’t!

From this we are supposed to derive something about the types of A and B, that is, whether each is a knight or a knave. Notice that they cannot both be telling the truth, because they contradict each other. Thus, A’s statement cannot be true (because if they are both knights, they must both tell the truth.) This allows us to conclude that A must be a knave, because only a knave can say false things.

And what about B? B’s statement is true, because they are certainly not both knights, and since only a knight can make a true statement, B must be a knight. So the (unique) solution to this puzzle is that A is a knave and B is a knight.

The next day, you meet three new inhabitants: A, B, C. (Not the same A and B from earlier!)

A: Exactly one of us is a knave.

B: At least one of us is a knight.

C: None of us is a knave.

Which inhabitants are knights, and which are knaves?

If you enjoy these kind of problems, you can find more in Raymond Smullyan's puzzle books.
The books use mostly simple words - give it a try.
You can download the first book he wrote (here)[http://www.pdfarchive.info/pdf/S/Sm/Smullyan_Raymond_-_What_is_the_Name_of_This_Book.pdf]