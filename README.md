# FizzBuzz

I took up this program because it does not require the users to know any specific domain. Even people who are new to OOPS can do this in a procedural language. In other words, the purpose is to just learn TDD. Rest is not of concern.

## How am I going to do it?
Different versions of TDD implementation of FizzBuzz. Each branch will have another version of the implementation with `master` branch not having any code. 

To simulate real behavior as closely as possible and to drive the message that even toy code can have "change requests", I have added the requirements in two parts.

## Requirements:
### Iteration 1:
The requirements for the program are as follows:
 - Print numbers from 1 to 100.
 - But for the multiples of 3, print `Fizz` instead and for multiples of 5, print `Buzz`.
 - For multiples of both, print `FizzBuzz`.
 - When multiple rules are satisfied the order to be used is:
  - Multiple of 3
  - Multiple of 5

#### Expected Output
```
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
16
17
Fizz
19
Buzz
Fizz
22
23
Fizz
Buzz
26
Fizz
28
29
FizzBuzz
31
32
Fizz
34
Buzz
Fizz
37
38
Fizz
Buzz
41
Fizz
43
44
FizzBuzz
46
47
Fizz
49
Buzz
Fizz
52
53
Fizz
Buzz
56
Fizz
58
59
FizzBuzz
61
62
Fizz
64
Buzz
Fizz
67
68
Fizz
Buzz
71
Fizz
73
74
FizzBuzz
76
77
Fizz
79
Buzz
Fizz
82
83
Fizz
Buzz
86
Fizz
88
89
FizzBuzz
91
92
Fizz
94
Buzz
Fizz
97
98
Fizz
Buzz

```

### Iteration 2:
 - If the number contains a 3 (for example 23), print `Bizz`.
 - If the number contains a 5, print `Fuzz` (if it contains multiple 3s or 5s, just print one `Bizz` or `Fuzz`).
 - If the number contains more than one of these attributes, print every word (for example 33 prints `FizzBizz`, as 33 is both a multiple of 3 and contains the digit 3).
 - When multiple rules are satisfied the order to be used is:
  - Multiple of 3
  - Multiple of 5
  - Number contains 3
  - Number contains 5

#### Expected Output
```
1
2
FizzBizz
4
BuzzFuzz
Fizz
7
8
Fizz
Buzz
11
Fizz
Bizz
14
FizzBuzzFuzz
16
17
Fizz
19
Buzz
Fizz
22
Bizz
Fizz
BuzzFuzz
26
Fizz
28
29
FizzBuzzBizz
Bizz
Bizz
FizzBizz
Bizz
BuzzBizzFuzz
FizzBizz
Bizz
Bizz
FizzBizz
Buzz
41
Fizz
Bizz
44
FizzBuzzFuzz
46
47
Fizz
49
BuzzFuzz
FizzFuzz
Fuzz
BizzFuzz
FizzFuzz
BuzzFuzz
Fuzz
FizzFuzz
Fuzz
Fuzz
FizzBuzz
61
62
FizzBizz
64
BuzzFuzz
Fizz
67
68
Fizz
Buzz
71
Fizz
Bizz
74
FizzBuzzFuzz
76
77
Fizz
79
Buzz
Fizz
82
Bizz
Fizz
BuzzFuzz
86
Fizz
88
89
FizzBuzz
91
92
FizzBizz
94
BuzzFuzz
Fizz
97
98
Fizz
Buzz
```
