0x11. C - printf Group Projects printf - formatted output conversion #include "main.h" int _printf...);

Description The _printf() function produce output according to a format as described below. Also, write output to stdout, the standard output stream. The _printf() function write the output under the control of a format string that specifies how subsequent arguments (or arguments accessed via the variable-length argument facilities of stdarg(3) are converted for output.

Format of the format string The format string is a character string, beginning and ending inits initial shift state, if any. The format string is composed of zero or more directives: ordinary characters (not %), which are copied unchanged to the output stream; and conversion specifications, each of which results in fetching zero or more subsequent arguments. Each conversion specification is introduced by the character % and ends with conversion specifier.

Conversion specifiers A character that specifies the type of conversion to be applied. The conversion specifiers and their meaning are:

d, i: The int argument should be signed decimal notation, and the resulting number is written.
c: The int argument is converted to a char, and the resulting character is written.
s: The const char * argument is expected to be a pointer to an array of char
Author _printf() is written and maintained by Chukwudi Egoebichi and OKIIDEMUDIA EDOBHEN BRENDA
