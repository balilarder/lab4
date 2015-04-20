question A: overloading function "average", but the arguments are different, so can be encoded with identifiers.
			result: 00000000004004b4 T _Z7averagePdRd    The first is a pointer to double, the second is too.
					00000000004004e2 T _Z7averageif		 The first is a integer, the second is a float.
					000000000040050a T main
question B: result is
1 8
4 8
4 8
8 8
Because char, int, float, double are basic type, which use 1, 4, 4, 8 bytes respectively, but pointer represent an
adddress in the memory and has nothing to do with the type which it point to, always have same bytes. 
