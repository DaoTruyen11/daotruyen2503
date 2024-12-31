---
title: "Bài 5: Câu lệnh điều kiện trong Java"
date: 2024-12-31T12:00:00+07:00
draft: false
author: "Tên của bạn"
tags:
  - Java
  - Điều kiện
  - If-else
  - Switch
image: /images/java-conditions.jpg
description: "Tìm hiểu cách xử lý logic điều kiện với if-else và switch trong Java."
toc: true
---

## Câu lệnh if-else
```java
public class IfElseExample {
    public static void main(String[] args) {
        int age = 18;

        if (age >= 18) {
            System.out.println("Bạn đủ tuổi bầu cử.");
        } else {
            System.out.println("Bạn chưa đủ tuổi bầu cử.");
        }
    }
}