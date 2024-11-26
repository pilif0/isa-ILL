# Deep Embedding of Intuitionistic Linear Logic

In this entry we formalise intuitionistic linear logic (ILL) with a deep embedding of propositions, and shallow and deep embeddings of deductions.
We introduce the logic with an _explicit_ exchange rule, meaning sequents have a list of propositions as antecedents.
We then prove that sequents that differ only in the order of their antecedents are equivalently valid, representing the alternative _implicit_ exchange rule.
The deep embedding of deductions allows for direct construction, manipulation and verification of ILL deductions.

This is the development version of our Archive of Formal Proofs [entry](https://www.isa-afp.org/entries/ILL.html).

## Requirements
This formalisation is tested with Isabelle 2024, but should work with most modern versions.
It relies on the `HOL-Combinatorics` session, which is part of the Isabelle distribution.

## Installation
To use this formalisation, add it as a component to your Isabelle installation:
```
isabelle components -u PATH/TO/REPO
```

If you have a local copy of the AFP as a component, disable the corresponding entry to avoid a clash.
You can do this by removing it from the AFP `ROOTS` file, or by renaming either entry if you want to use both versions.
