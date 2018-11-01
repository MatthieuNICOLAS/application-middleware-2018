# Additional ressources

These slides are meant to be read as a complement of the following [position paper](https://github.com/MatthieuNICOLAS/application-middleware-2018/blob/master/position-paper/position-paper.pdf).
The goal is to provide more insight on LogootSplit and the proposed renaming mechanism for those interested.

# TODO

- [ ] Add a slide about the order relation between identifiers
- [ ] Add a slide linking the different parts of identifiers to the different constraints
- [ ] Add slides about handling concurrent updates to a *rename* operation
    - [ ] Illustrate that we can not just apply the concurrent operation
    - [ ] Illustrate proposed approach rewriting the identifiers before applying the concurrent operation
    - [ ] Describe metadata introduced to define the rewriting rules : the *renamingMap*
