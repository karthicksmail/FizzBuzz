# FizzBuzz

I took up this program because it does not require the users to know any specific domain. Even people who are new to OOPS can do this in a procedural language. In other words, the purpose is to just learn TDD. Rest is not of concern.

## How am I going to do it?
Different versions of TDD implementation of FizzBuzz. Each branch will have another version of the implementation with `master` branch not having any code. 

To simulate real behavior as closely as possible and to drive the message that even toy code can have "change requests", I have added the requirements in two parts.

## Requirements:
### Iteration 1:
The requirements for the program are as follows:
Print numbers from 1 to 100.
But for the multiples of 3, print `Fizz` instead and for multiples of 5, print `Buzz`. \
For multiples of both, print `FizzBuzz`.

#### Expected Output
1
2
Fizz
3
4
Buzz
5
Fizz
6
7
8
Fizz
9
Buzz
10
11
Fizz
12
13
14
Fizz
Buzz
16
17
Fizz
18
19
Buzz
20
Fizz
21
22
23
Fizz
24
Buzz
25
26
Fizz
27
28
29
Fizz
Buzz
31
32
Fizz
33
34
Buzz
35
Fizz
36
37
38
Fizz
39
Buzz
40
41
Fizz
42
43
44
Fizz
Buzz
46
47
Fizz
48
49
Buzz
50
Fizz
51
52
53
Fizz
54
Buzz
55
56
Fizz
57
58
59
Fizz
Buzz
61
62
Fizz
63
64
Buzz
65
Fizz
66
67
68
Fizz
69
Buzz
70
71
Fizz
72
73
74
Fizz
Buzz
76
77
Fizz
78
79
Buzz
80
Fizz
81
82
83
Fizz
84
Buzz
85
86
Fizz
87
88
89
Fizz
Buzz
91
92
Fizz
93
94
Buzz
95
Fizz
96
97
98
Fizz
99
Buzz
100

### Iteration 2:
If the number contains a 3 (for example 23), print `Bizz`.
If the number contains a 5, print `Fuzz` (if it contains multiple 3s or 5s, just print one `Bizz` or `Fuzz`).
If the number contains more than one of these attributes, print every word (for example 33 prints `FizzBizz`, as 33 is both a multiple of 3 and contains the digit 3).

#### Expected Output

