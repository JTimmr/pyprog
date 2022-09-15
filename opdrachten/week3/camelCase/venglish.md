# camelCase or snake_case?

In general, snake_case is used for naming variables or functions in Python, where a `_` separates the individual words. Some people prefer using camelCase, where the very first letter is lower case, and the first letter of each new word is upper case. This ensures the words within the name are distinguishable.

You might want to write a certain function named `check`, but if it needs to be more specific, `checkInput` or `checkInputFromUser` could be more suitable. As mentioned before, it's customary to use `snake_case` in Python. That is why you are gonna write a program to convert names into that format.


## Assignment

Write, in a file named `camel.py`, a program which converts the name from camelCase to snake_case.

## Code

For this assignment you are going to write your own function, as before. Design your program as described below. Complete the docstrings with doctests and any other explanation you deem necessary.

    def convert(name: str) -> str:
        """
        Convertert a name from camelCase to snake_case
        """

    if __name__ == '__main__':
        Prompt the user for an answer, call your function, and print the result.

## Examples

Ultimately, your program has to produce output like the examples below.

    $ python camel.py
    camelCase: check
    snake_case: check

    $ python camel.py
    camelCase: checkInput
    snake_case: check_input

    $ python camel.py
    camelCase: checkInputFromUser
    snake_case: check_input_from_user
