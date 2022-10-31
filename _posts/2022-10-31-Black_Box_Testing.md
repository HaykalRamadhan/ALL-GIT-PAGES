---
layout: post
title: Black Box Testing
published: true
---
<style>
p.normal{
  font-weight: normal;
  text-align: justify;
}
</style>

## What is Black Box Testing?

<p class="normal">
Black Box Testing is a software testing method in which the functionalities of software applications are tested without having knowledge of internal code structure, implementation details and internal paths. Black Box Testing mainly focuses on input and output of software applications and it is entirely based on software requirements and specifications. It is also known as Behavioral Testing.
</p>
  
![image](https://www.imperva.com/learn/wp-content/uploads/sites/13/2020/03/thumbnail_Black-box.jpg)

<p class="normal">
The above Black-Box can be software you want to test. For example an operating system such as Linux, Windows, a website like Google, Youtube or even a database like Oracle. Under Black Box Testing, you can test these applications by just focusing on the inputs and outputs without knowing their internal code implementation.
</p>

## Equivalent Class Partitioning

<p class="normal">
Equivalence Partitioning or also known as Equivalence Class Partitioning (ECP). It is a software testing technique or black-box testing that divides input domain into classes of data, and with the help of these classes of data, test case can be derived. An ideal test case identifies class of error that might require many arbitary test cases to be executed before general error is observed.

In equivalence partitioning, equivalence classes are evaluated for given input conditions. Whenever any input is given, then type of input condition is checked, then for this input conditions, Equivalence class represents or describes set of valid or invalid states.
</p>

**Guidelines for Equivalence Partitioning:**
- If the range condition is given as an input, then one valid and two invalid equivalence classes are defined.
- If a specific value is given as input, then one valid and two invalid equivalence classes are defined.
- If a member of set is given as an input, then one valid and one invalid equivalence class is defined.
- if Boolean no. is given as an input condition, then one valid and one invalid equvalence class is defined.

## Boundary Value Analysis
<p class="normal">
Boundary Value Analysis (BVA) is one of the functional testings. Functional testing is a type of software testing in which the system is tested against the functional requirements of the system. It is conducted to ensure that the requirements are properly satisfied by the application. Functional testing verifies that each function of the software application works in conformance with the requirement and specification.
</p>