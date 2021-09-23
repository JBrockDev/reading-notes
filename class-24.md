# Class 24 - Reading Notes

## Functional Programming Concepts

1. Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data — Wikipedia
2. A pure function is one that returns the same results given the same arguments and also does not cause any side effects, ie uses only variables created within it's own scope.
3. A pure function is easier to test because it will always yield the same result given the same input.
4. An immutable variable is one that cannot have it's value changed. A new variable must be created in it's place if you want a different value.
5. Referential transparency is always providing the same output given the same input. A combination of pure functions and immutable data.

## Node JS Tutorial - Modules and require()

1. A module is another javascript file.
2. The require word imports a module and declares the global variable(s) within the file the require is called in.
3. Use require(filePath)
4. You must define exports via module.exports within the module.
