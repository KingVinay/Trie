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

Check Starting INFO with -> startsWith

``` Java
//startswith checks whether information starts with particular string or not
objName.startsWith("Se");

Check Empty or not with -> isEmpty

``` Java
// isEmpty checks whether trie is empty or not
objName.isEmpty(objName.root);

