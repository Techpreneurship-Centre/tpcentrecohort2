![xx](https://launchlab.co.za/wp-content/uploads/2020/08/cropped-LaunchLab-Logo.png)

# Technepreneurship Centre Coding Challenge
Welcome to the Technepreneurship Centre Coding Challenge!

Please read through the instructions carefully - good luck :)


# Instructions
## Overview
There are **6 questions** in total, of which **the first 4 are mandatory**. Please also give the non-mandatory ones a go! These challenges and questions are industry-standard, and should also be good practice for you.

We'll be testing your knowledge on the following:
* Programming fundamentals
* Data structures
* Basic algorithms


## Programming language
The questions can be completed in any language.

Please just **use a single programming language** in which you provide your answers.


## Uploading your answers
* Please upload your code in the *Answers* folder.
* Please upload each question in a **separate file** 
* Please name the files in the following format: *question-1*, *question-2*, etc.


## Form
Please make sure to fill in all the info in the form emailed to you in conjuction with submitting your challenge on GitHub.


## Timing
We ask you to please time yourself when completing the challenges. The timing is to help you track how efficient you are with the challenges and no other reason.

Please try these challenges **yourself**, and be honest on how long you took to solve them. If you just google everything, it's really not to the benefit of yourself or to develop your skills.


## Comments
Please make sure to comment your code, so we can look at your train of thought.
![Image of Comment Joke](https://i.imgflip.com/owzm8.jpg)



&nbsp;

# Questions
## Question 1
Write a function that computes the list of the first `100` Fibonacci numbers.

By definition, the first two numbers in the Fibonacci sequence are `0` and `1`, and each subsequent number is the sum of the previous two.

As an example, the first 10 Fibonacci numbers are: `0`, `1`, `1`, `2`, `3`, `5`, `8`, `13`, `21`, and `34`.

Please start your timer before you attempt this challenge.

&nbsp;

## Question 2
Given an array of integers, return how many elements of the array contain an even number of digits, and how many contain an uneven number of digits.

For example, for the array `[555, 901, 482, 1771]`, the answer would be:
* Even number: 1 element (`482`)
* Odd numbers: 3 elements (`555`, `901`, `1771`)

Please start your timer before you attempt this challenge.


&nbsp;

## Question 3
Given a collection of intervals, merge all overlapping intervals.

For example:
For the input intervals of `[[1,3], [2,6], [8,10], [15,18]]`, the output would be `[[1,6], [8,10], [15,18]]`.
Since intervals `[1,3]` and `[2,6]` overlap, they are merged into `[1,6]`.

Please start your timer before you attempt this challenge.


&nbsp;

## Question 4
Write a function that converts a Roman numeral into an integer value.

Roman numerals are represented by seven different symbols: `I`, `V`, `X`, `L`, `C`, `D` and `M`.

Their values are:
`I`: `1`
`V`: `5`
`X`: `10`
`L`: `50`
`C`: `100`
`D`: `500`
`M`: `1000`

Roman numerals are usually written largest to smallest from left to right.

For example:
* `3` is written as `III`
* `28` is written as `XXVIII`

However, there are some exceptions, to Roman numeral conversion: For example, the numeral for `4` is not `IIII`. Instead, the number `four` is written as `IV` (as the `1` is before the `5`, it is subtracted making `1`. The same principle applies to the number `9`, which is written as `IX`.

There are six instances where subtraction is used:
* `I` can be placed before `V (5)` and `X (10)` to make `4` and `9`. 
* `X` can be placed before `L (50)` and `C (100)` to make `40` and `90`. 
* `C` can be placed before `D (500)` and `M (1000)` to make `400` and `900`.

Thus, given a roman numeral, convert it to an integer. You can assume that input is guaranteed to be within the range from `1` to `3999`.

Please start your timer before you attempt this challenge.

&nbsp;

## Question 5
Given a sorted array, remove the duplicates such that each element appear only once and return the new length.

For example, for the array `[0, 0, 1, 1, 1, 2, 2, 3, 3, 4, 5, 5]`, your function should return length = `6`, with the first five elements of being modified to `0`, `1`, `2`, `3`, `4`, and `7`, respectively.

Please start your timer before you attempt this challenge.

&nbsp;

## Question 6

Given an array of integers `nums` and an integer `k`, determine whether there are two distinct indices `i` and `j` in the array where `nums[i]` = `nums[j]` and the absolute difference between `i` and `j` is less than or equal to `k`.

Example:
For nums = `[0,1,2,3,5,2]` and `k=3`, the output should be `containsCloseNums(nums, k) = true`.

There are two `2`s in `nums`, and the absolute difference between their positions is exactly `3`.


For nums = `[0,1,2,3,5,2]` and `k=2`, the output should be `containsCloseNums(nums, k) = false`.

The absolute difference between the positions of the two `2`s is `3`, which is more than `k`.

Please start your timer before you attempt this challenge.


