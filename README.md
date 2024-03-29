# marginalia

The goal of this project is to assist in locating text within a literary corpus that was influenced by the author's reading of external texts, which we refer to as source passages. The literary corpus being used for developement comes from the writing of Herman Melville (specifically, the project Gutenberg text of *Moby Dick*) and his readings of source passages come from the Melville [Marginalia  project](http://melvillesmarginalia.org/).

The approach being taken is to search through the literary corpus looking for key terms, their stems, and their synomyms taken from the source passages. After identifying them in the corpus, the program outputs a score for identified text based on the number of hits and the distances among the hits to produce a value that indicates the likelihood of a connection existing between the corpus and the source passages.

