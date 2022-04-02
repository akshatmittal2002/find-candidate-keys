# Find-Candidate-Keys

Finding all `candidate keys` for a given relation.

Given a particular relation and a set of functional dependencies over it, this program outputs the list of all candidate keys. The list will be sorted based on `size`. Within the keys of same size, the sorting order follows the `alphanumeric order`.
<br><br>

### Input:
`Line 1` contains number of attributes in the relation. In general, if the relation has `N` attributes then they are `1, 2, 3, ... N`.<br>
`Line 2` contains number of functional dependencies.<br>
From `Line 3` onwards Functional Dependencies `(FD)` are described. Each FD is described using two lines. First line describes the left side or antecedent and the second line describes the right side or consequent. If the antecedent or the consequent consists of multiple attributes then they are separated by a space. In general, if there are `M` FDs on a relation, there will be `2M` lines to describe those FDs.
<br><br>

### Output:
`Line 1` contains number of candidate keys in given relation.<br>
From `Line 2` onwards, each candidate key is described using one line. If the candidate key consists of more than one attribute, then the attributes are separated by space terminated by `\n`.