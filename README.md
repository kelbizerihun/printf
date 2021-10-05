0x11. C - printf

'b' - Binary. Outputs the number in base 2.

'c' - Character. Converts the integer to the corresponding
      Unicode character before printing.

'd' - Decimal Integer. Outputs the number in base 10.

'o' - Octal format. Outputs the number in base 8.

'x' - Hex format. Outputs the number in base 16, using lower-
      case letters for the digits above 9.

'X' - Hex format. Outputs the number in base 16, using upper-
      case letters for the digits above 9.

'n' - Number. This is the same as 'd', except that it uses the
      current locale setting to insert the appropriate
      number separator characters.

'' (None) - the same as 'd'

'e' - Exponent notation. Prints the number in scientific
      notation using the letter 'e' to indicate the exponent.

'E' - Exponent notation. Same as 'e' except it converts the
      number to uppercase.

'f' - Fixed point. Displays the number as a fixed-point
      number.

'F' - Fixed point. Same as 'f' except it converts the number
      to uppercase.

'g' - General format. This prints the number as a fixed-point
      number, unless the number is too large, in which case
      it switches to 'e' exponent notation.

'G' - General format. Same as 'g' except switches to 'E'
      if the number gets to large.

'n' - Number. This is the same as 'g', except that it uses the
      current locale setting to insert the appropriate
      number separator characters.

'%' - Percentage. Multiplies the number by 100 and displays
      in fixed ('f') format, followed by a percent sign.

'' (None) - similar to 'g', except that it prints at least one
      digit after the decimal point.

Integer types such as short, int, long, long long, and their unsigned variants,

are specified by using d, i, o, u, x, and X. Floating-point types such as floa

t, double, and long double, are specified by using a, A, e, E, f, F, g, and G.

By default, unless they're modified by a size prefix, integer arguments are coe

rced to int type, and floating-point arguments are coerced to double. On 64-bit

systems, an int is a 32-bit value; so, 64-bit integers will be truncated when

they're formatted for output unless a size prefix of ll or I64 is used. Pointer

types that are specified by p use the default pointer size for the platform.

Standard Format Specifiers

'<' - Forces the field to be left-aligned within the available
      space (This is the default.)

'>' - Forces the field to be right-aligned within the
      available space.

'=' - Forces the padding to be placed after the sign (if any)
      but before the digits.  This is used for printing fields
      in the form '+000000120'. This alignment option is only
      valid for numeric types.

'^' - Forces the field to be centered within the available
      space.
      

'+'  - indicates that a sign should be used for both
       positive as well as negative numbers

'-'  - indicates that a sign should be used only for negative
       numbers (this is the default behavior)

' '  - indicates that a leading space should be used on
       positive numbers.

