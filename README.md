# Isomorphic String

##### The isIsomorphic algorithm checks if two strings, str1 and str2, are isomorphic. Isomorphic strings have a one-to-one mapping of characters from str1 to str2, preserving the order of characters. It first compares the lengths of the input strings, returning false if they are different. Then, it uses a map to keep track of the mappings and a set to ensure that multiple characters do not map to the same character. For each character in str1, it checks if it already has a mapping; if yes, it ensures that the mapping is consistent with the character in str2.

##### If not, it adds the mapping to the map and checks if the character in str2 has already been mapped to. If there is a conflict at any point, the function returns false, indicating that the strings are not isomorphic. Otherwise, it returns true, indicating that the strings are isomorphic. The time complexity of the algorithm is O(n), where n is the length of the input strings, as it iterates through each character once.

#### Dear Students, Check out the live app [here](https://kdeepika-brs.github.io/isomorphic-string/).


