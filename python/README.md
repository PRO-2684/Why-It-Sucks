# Why Python Sucks

> [!NOTE]
> Disclaimer: Images [created with AI](https://chatgpt.com/share/69e85c28-b450-83ea-af3a-4ae8505c1fb8).

## Dependency

<details><summary>It does not generate a `requirements.txt` file for a project automatically.</summary>

![no-requirements](./1-no-requirements.png)

</details>

<details><summary>It does not pin dependencies by default, and `import` names and `pip install` names are not always the same.</summary>

![requirements-not-pinned](./2-requirements-not-pinned.png)

</details>

## Typing

<details><summary>VERY poor IDE support.</summary>

![unknown-type](./3-unknown-type.png)

</details>

<details><summary>`argparse` is not typed.</summary>

![argparse-vs-tap](./4-argparse-vs-tap.png)

Consider using [typed-argument-parser](https://github.com/swansonk14/typed-argument-parser) instead.

</details>

## API Design

<details><summary>Free function instead of methods.</summary>

![free-function](./5-free-function.png)

(You still need to cope with iterators if the list is large)

</details>

<details><summary>str.join instead of list.join.</summary>

![str-join](./6-str-join.png)

</details>

<!--## Importing-->

<!-- Circular import: ImportError: cannot import name 'SomeClass' from partially initialized module 'some_module' (most likely due to a circular import) -->

<!-- Unresolved imports -->
