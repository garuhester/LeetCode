Implement atoi to convert a string to an integer.

Hint: Carefully consider all possible input cases. If you want a challenge, please do not see below and ask yourself what are the possible input cases.

Notes: It is intended for this problem to be specified vaguely (ie, no given input specs). You are responsible to gather all the input requirements up front.

Update (2015-02-10):
The signature of the C++ function had been updated. If you still see your function signature accepts a const char * argument, please click the reload button  to reset your code definition.

---

Requirements for atoi:
The function first discards as many whitespace characters as necessary until the first non-whitespace character is found. Then, starting from this character, takes an optional initial plus or minus sign followed by as many numerical digits as possible, and interprets them as a numerical value.

The string can contain additional characters after those that form the integral number, which are ignored and have no effect on the behavior of this function.

If the first sequence of non-whitespace characters in str is not a valid integral number, or if no such sequence exists because either str is empty or it contains only whitespace characters, no conversion is performed.

If no valid conversion could be performed, a zero value is returned. If the correct value is out of the range of representable values, INT_MAX (2147483647) or INT_MIN (-2147483648) is returned.

>1.这个函数在第一个非空白字符出现可以丢弃尽量多的空白字符。然后从这个非空白字符开始，获取一个初始的加号或者减号，然后之后的数字字符会被转成一个数。
2.这个字符串在形成一个数之后可以包含其他字符，函数应该不受他们影响并忽略它们。
3.如果第一个非空白字符不是一个合法的数字字符，或者这个序列不存在即为空或者全为空白字符，不进行任何转换。
4.如果没有进行转换，函数应该返回0值。如果正确的数值越界了，应该返回2147483647或者-2147483648。
