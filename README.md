
# LeetCode Challenge D45
## Achievements
[![image.png](https://i.postimg.cc/Y2gHGfb3/image.png)](https://postimg.cc/qgkYWnfh)

This solution outperformed 100% of Java users on LeetCode according to runtime metrics and 78.85% according to Memory Metrics.


## Overview

Welcome to my LeetCode solution repository! This project addresses the coding challenge presented by [2185. Counting Words With a Given Prefix](https://leetcode.com/problems/counting-words-with-a-given-prefix/). Below, you'll find details about the problem, my approach to solving it, and the implemented solution.

## Problem Statement
You are given an array of strings  `words`  and a string  `pref`.
Return  _the number of strings in_ `words` _that contain_ `pref` _as a  **prefix**_.
A  **prefix**  of a string  `s`  is any leading contiguous substring of  `s`.

**Example**
>**Input:** words = ["pay","**at**tention","practice","**at**tend"], `pref` = "at"
>
>**Output:** 2
>
>**Explanation:** The 2 strings that contain "at" as a prefix are: "**at**tention" and "**at**tend".

**Language Used**
> Java

**Difficulty**
> Easy

## Solution Overview
The implemented solution employs a loop that iterates through each element in the array, utilizing the `startsWith` method to determine whether the current string begins with the given prefix. If a match is found, the count variable increments, ultimately capturing the total number of strings meeting the specified criteria.
