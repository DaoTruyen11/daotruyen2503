---
title: "Bài 7: Hàm trong Java"
date: 2024-12-31T14:00:00+07:00
draft: false
author: "Tên của bạn"
tags:
  - Java
  - Hàm
  - Function
image: /images/java-functions.jpg
description: "Tìm hiểu cách định nghĩa và sử dụng hàm trong Java."
toc: true
---

## Định nghĩa hàm
```java
public class FunctionExample {
    public static void main(String[] args) {
        int result = sum(5, 10);
        System.out.println("Tổng: " + result);
    }

    // Hàm tính tổng
    public static int sum(int a, int b) {
        return a + b;
    }
}