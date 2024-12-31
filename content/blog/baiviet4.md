---
title: "Bài 4: Toán tử và biểu thức trong Java"
date: 2024-12-31T11:00:00+07:00
draft: false
author: "Tên của bạn"
tags:
  - Java
  - Toán tử
  - Biểu thức
image: /images/java-operators.jpg
description: "Khám phá các loại toán tử và cách sử dụng chúng trong Java."
toc: true
---

## Toán tử trong Java
Toán tử là ký hiệu đặc biệt được sử dụng để thực hiện các phép toán.

### Các loại toán tử chính
1. **Toán tử số học**: `+`, `-`, `*`, `/`, `%`
2. **Toán tử so sánh**: `==`, `!=`, `>`, `<`, `>=`, `<=`
3. **Toán tử logic**: `&&`, `||`, `!`
4. **Toán tử gán**: `=`, `+=`, `-=`, `*=`, `/=`
5. **Toán tử tăng giảm**: `++`, `--`

### Ví dụ
```java
public class OperatorsExample {
    public static void main(String[] args) {
        int a = 10, b = 5;
        
        // Toán tử số học
        System.out.println("Tổng: " + (a + b));
        System.out.println("Hiệu: " + (a - b));
        System.out.println("Tích: " + (a * b));
        System.out.println("Thương: " + (a / b));
        System.out.println("Phần dư: " + (a % b));

        // Toán tử so sánh
        System.out.println("a lớn hơn b? " + (a > b));

        // Toán tử logic
        boolean x = true, y = false;
        System.out.println("x && y: " + (x && y));
        System.out.println("x || y: " + (x || y));
    }
}
