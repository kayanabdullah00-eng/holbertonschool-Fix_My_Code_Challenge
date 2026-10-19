# Fix My Code Challenge

## Description

This project is part of the **Fix My Code Challenge**.

The goal is to identify and fix issues in an existing codebase without rewriting the entire project.

## Task 0: FizzBuzz

The `0-fizzbuzz.py` script prints numbers from `1` to a given number.

Rules:

- Multiples of `3` print `Fizz`
- Multiples of `5` print `Buzz`
- Multiples of both `3` and `5` print `FizzBuzz`
- Other numbers are printed normally

### Bug Fixed

The original implementation printed `Fizz` instead of `FizzBuzz` for numbers divisible by both `3` and `5`, such as `15`.

The condition checking divisibility by both `3` and `5` was moved before the individual `Fizz` and `Buzz` conditions.

## Usage

```bash
./0-fizzbuzz.py 50
```

Example output:

```text
1 2 Fizz 4 Buzz Fizz 7 8 Fizz Buzz 11 Fizz 13 14 FizzBuzz
```

## Environment

- Ubuntu 20.04 LTS
- Python 3

## Repository

**GitHub repository:** `holbertonschool-Fix_My_Code_Challenge`

**Directory:** `challenge`

**File:** `0-fizzbuzz.py`
