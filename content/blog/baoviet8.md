---
title: "Bài 8: Mảng và danh sách trong Java"
date: 2024-12-31T15:00:00+07:00
draft: false
author: "Minh Quang"
tags:
  - Java
  - Mảng
  - List
image: /images/java-arrays.jpg
description: "Làm việc với mảng và danh sách trong Java."
toc: true
---

## Mảng
```java
public class ArrayExample {
    public static void main(String[] args) {
        int[] numbers = {1, 2, 3, 4, 5};
        for (int num : numbers) {
            System.out.println(num);
        }
    }
}
Danh sách (List)
java
Sao chép mã
import java.util.ArrayList;

public class ListExample {
    public static void main(String[] args) {
        ArrayList<String> names = new ArrayList<>();
        names.add("Nam");
        names.add("An");
        names.add("Hoa");

        for (String name : names) {
            System.out.println(name);
        }
    }
}