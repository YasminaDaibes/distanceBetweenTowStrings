# distanceBetweenTowStrings
recursive function that returns the distance between two given strings.
distance between two strings s1,s2 is the number of chars the we can remove from s2 to get the same string s1.

For call distance("abc", "abc"), result is 0

For call distance("abc", "abcd"), result is 1

For call distance("abc", "txatbc"), result is 3

For call distance("abc", "txatbd"), result is -1
