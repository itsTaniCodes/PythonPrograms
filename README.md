# PythonPrograms — DevOps Assignment 3

This repository follows the folder structure and file names specified in the Assignment 3 PDF.

## Structure

```text
PythonPrograms/
├── Code/
│   ├── 01_even_odd.py
│   ├── ...
│   └── 20_word_frequency.py
└── Test_Code/
    ├── test_01_even_odd.py
    ├── ...
    └── test_20_word_frequency.py
```

Each solution in `Code/` is implemented using a function (`def`). Each matching test file imports the solution and verifies it using Python `assert`. Every test file prints `All test cases passed.` when all assertions succeed.

## Run a test

From the repository root:

```bash
python Test_Code/test_01_even_odd.py
```

You can also use pytest if installed:

```bash
pytest Test_Code/test_01_even_odd.py -v
```

## Important assumptions

- Program 15 returns the second **distinct** largest value.
- Program 18 assumes the list contains numbers from `1` through `n` with exactly one number missing.
- Program 13 checks palindromes case-insensitively and ignores spaces/punctuation.
- Program 20 counts words case-insensitively and ignores punctuation.
- Program 11 counts only alphabetic characters as vowels/consonants; spaces, digits and punctuation are ignored.
- Program 12 reverses the string without using `[::-1]`.

## One-file-at-a-time Git commands

The assignment specifically says not to use `git add .`. Add, commit, and push each file separately.

### Program 1

```bash
git status
git add Code/01_even_odd.py
git commit -m "Add even odd program"
git push origin main

git status
git add Test_Code/test_01_even_odd.py
git commit -m "Add even odd test cases"
git push origin main
```

### Program 2

```bash
git status
git add Code/02_largest_of_three.py
git commit -m "Add largest of three program"
git push origin main

git status
git add Test_Code/test_02_largest_of_three.py
git commit -m "Add largest of three test cases"
git push origin main
```

### Program 3

```bash
git status
git add Code/03_pos_neg_zero.py
git commit -m "Add positive negative zero program"
git push origin main

git status
git add Test_Code/test_03_pos_neg_zero.py
git commit -m "Add positive negative zero test cases"
git push origin main
```

### Program 4

```bash
git status
git add Code/04_factorial.py
git commit -m "Add factorial program"
git push origin main

git status
git add Test_Code/test_04_factorial.py
git commit -m "Add factorial test cases"
git push origin main
```

### Program 5

```bash
git status
git add Code/05_fibonacci_series.py
git commit -m "Add fibonacci series program"
git push origin main

git status
git add Test_Code/test_05_fibonacci_series.py
git commit -m "Add fibonacci series test cases"
git push origin main
```

### Program 6

```bash
git status
git add Code/06_prime_number.py
git commit -m "Add prime number program"
git push origin main

git status
git add Test_Code/test_06_prime_number.py
git commit -m "Add prime number test cases"
git push origin main
```

### Program 7

```bash
git status
git add Code/07_primes_in_range.py
git commit -m "Add primes in range program"
git push origin main

git status
git add Test_Code/test_07_primes_in_range.py
git commit -m "Add primes in range test cases"
git push origin main
```

### Program 8

```bash
git status
git add Code/08_reverse_number.py
git commit -m "Add reverse number program"
git push origin main

git status
git add Test_Code/test_08_reverse_number.py
git commit -m "Add reverse number test cases"
git push origin main
```

### Program 9

```bash
git status
git add Code/09_palindrome_number.py
git commit -m "Add palindrome number program"
git push origin main

git status
git add Test_Code/test_09_palindrome_number.py
git commit -m "Add palindrome number test cases"
git push origin main
```

### Program 10

```bash
git status
git add Code/10_sum_of_digits.py
git commit -m "Add sum of digits program"
git push origin main

git status
git add Test_Code/test_10_sum_of_digits.py
git commit -m "Add sum of digits test cases"
git push origin main
```

### Program 11

```bash
git status
git add Code/11_vowels_consonants.py
git commit -m "Add vowels and consonants program"
git push origin main

git status
git add Test_Code/test_11_vowels_consonants.py
git commit -m "Add vowels and consonants test cases"
git push origin main
```

### Program 12

```bash
git status
git add Code/12_reverse_string.py
git commit -m "Add reverse string program"
git push origin main

git status
git add Test_Code/test_12_reverse_string.py
git commit -m "Add reverse string test cases"
git push origin main
```

### Program 13

```bash
git status
git add Code/13_palindrome_string.py
git commit -m "Add palindrome string program"
git push origin main

git status
git add Test_Code/test_13_palindrome_string.py
git commit -m "Add palindrome string test cases"
git push origin main
```

### Program 14

```bash
git status
git add Code/14_char_frequency.py
git commit -m "Add character frequency program"
git push origin main

git status
git add Test_Code/test_14_char_frequency.py
git commit -m "Add character frequency test cases"
git push origin main
```

### Program 15

```bash
git status
git add Code/15_second_largest.py
git commit -m "Add second largest program"
git push origin main

git status
git add Test_Code/test_15_second_largest.py
git commit -m "Add second largest test cases"
git push origin main
```

### Program 16

```bash
git status
git add Code/16_remove_duplicates.py
git commit -m "Add remove duplicates program"
git push origin main

git status
git add Test_Code/test_16_remove_duplicates.py
git commit -m "Add remove duplicates test cases"
git push origin main
```

### Program 17

```bash
git status
git add Code/17_common_elements.py
git commit -m "Add common elements program"
git push origin main

git status
git add Test_Code/test_17_common_elements.py
git commit -m "Add common elements test cases"
git push origin main
```

### Program 18

```bash
git status
git add Code/18_missing_number.py
git commit -m "Add missing number program"
git push origin main

git status
git add Test_Code/test_18_missing_number.py
git commit -m "Add missing number test cases"
git push origin main
```

### Program 19

```bash
git status
git add Code/19_find_duplicates.py
git commit -m "Add find duplicate elements program"
git push origin main

git status
git add Test_Code/test_19_find_duplicates.py
git commit -m "Add find duplicate elements test cases"
git push origin main
```

### Program 20

```bash
git status
git add Code/20_word_frequency.py
git commit -m "Add word frequency program"
git push origin main

git status
git add Test_Code/test_20_word_frequency.py
git commit -m "Add word frequency test cases"
git push origin main
```

## Submission checklist

- Repository name: `PythonPrograms`
- `Code/` contains 20 solution files.
- `Test_Code/` contains 20 matching test files.
- Every solution uses `def`.
- Every test file uses `assert`.
- Every test file prints `All test cases passed.`.
- Test each file before pushing.
- Add exactly one file at a time; do not use `git add .`.
- Use clear commit messages.
