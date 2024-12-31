---
title: "Bài 6: Vòng lặp trong Java"
date: 2024-12-31T13:00:00+07:00
draft: false
author: "Tên của bạn"
tags:
  - Java
  - Vòng lặp
image: /images/java-loops.png
description: "Khám phá các loại vòng lặp for, while và do-while trong Java."
toc: true
---

## Vòng lặp for
```java
public class ForLoopExample {
    public static void main(String[] args) {
        for (int i = 1; i <= 5; i++) {
            System.out.println("Lần lặp: " + i);
        }
    }
}
Vòng lặp while
java
Sao chép mã
public class WhileLoopExample {
    public static void main(String[] args) {
        int i = 1;
        while (i <= 5) {
            System.out.println("Lần lặp: " + i);
            i++;
        }
    }
}
Vòng lặp do-while
java
Sao chép mã
public class DoWhileExample {
    public static void main(String[] args) {
        int i = 1;
        do {
            System.out.println("Lần lặp: " + i);
            i++;
        } while (i <= 5);
    }
}