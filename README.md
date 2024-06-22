# Huffman-Coding
1. Run `AutocompleteMain` using `BruteAutoComplete` (complete in the starter code) to see how the autocomplete application works. 
2. Implement the `compare` method in the `PrefixComparator` class that is used in the `BinarySearchAutocomplete` class. Test with `TestTerm`.
3. Implement two methods in `BinarySearchLibrary`: `firstIndex` and `lastIndex`, both of which will use the `PrefixComparator` you completed in the previous step. Test with `TestBinarySearchLibrary`. **We recommend you try to finish these first three steps early**.
4. Finish implementing `BinarySearchAutocomplete` that extends `Autocompletor` by completing the `topMatches` method. This will use the `firstIndex` and `lastIndex` methods you wrote in the previous step and the code in `BruteAutocomplete.topMatches`  as a model. Test with `TestBinarySearchAutocomplete` and running `AutocompleteMain` using `BinarySearchAutocomplete`.
