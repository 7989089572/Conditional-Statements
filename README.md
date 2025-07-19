# Control Statements in Java - Conditional Statements Practice

Today I practiced Java conditional statements as part of control flow. Below are the 5 main types with examples:

---

## 1️⃣ if Statement

```java
int marks = 75;
if (marks > 50) {
    System.out.println("You passed!");
}
```

---

## 2️⃣ if-else Statement

```java
int age = 17;
if (age >= 18) {
    System.out.println("You are eligible to vote.");
} else {
    System.out.println("You are not eligible to vote.");
}
```

---

## 3️⃣ else-if Ladder

```java
int score = 85;
if (score >= 90) {
    System.out.println("Grade A");
} else if (score >= 80) {
    System.out.println("Grade B");
} else if (score >= 70) {
    System.out.println("Grade C");
} else {
    System.out.println("Fail");
}
```

---

## 4️⃣ nested if Statement

```java
int number = 20;
if (number > 0) {
    if (number % 2 == 0) {
        System.out.println("Positive Even Number");
    } else {
        System.out.println("Positive Odd Number");
    }
}
```

---

## 5️⃣ switch Statement

```java
int day = 3;
switch(day) {
    case 1: System.out.println("Monday"); break;
    case 2: System.out.println("Tuesday"); break;
    case 3: System.out.println("Wednesday"); break;
    default: System.out.println("Other Day");
}
```
