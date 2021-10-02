# Trie

For extremely fast prefix/fuzzy string searches, a data structure and associated algorithms are required.

## Usage

Create a Trie with:

``` Java
Trie objName = new Trie();
```
Add with -> insert:

``` Java
// insert can add information.
objName.insert("Search");
```
Search with -> search:

``` Java
// search can look for added information.
objName.search("Search");
```
Delete with -> delete

``` Java
// delete can delete added information
objName.delete("Search");

``` Java
objName.startsWith("Se");

``` Java
objName.isEmpty(objName.root);

