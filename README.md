# IP_Address_Converter_hex_decimal_octal_binary
This tool it provides a clear and concise representation of IP addresses in multiple numeral systems.

This Java program is an IP Address Converter that takes a user-inputted IP address and converts it into various formats, including Binary, Octal, Hexadecimal, and Decimal. It is designed to help network administrators, students, and anyone interested in understanding the different numerical representations of IP addresses.

**Functionality:**

- The program prompts the user to enter a valid IPv4 address (e.g., 192.168.1.1).
- It performs validation to ensure that the input is a correctly formatted IPv4 address.
- The program then converts the IP address into the following formats:
  - Binary
  - Octal
  - Hexadecimal
  - Decimal
- Each converted value is displayed to the user.
- If an invalid IP address is entered, the program displays an error message and prompts for re-entry.

**Usage:**

1. Run the program.
2. Enter a valid IPv4 address when prompted.
3. The program will display the IP address in Binary, Octal, Hex, and Decimal formats.
4. If an invalid address is entered, an error message will be shown. Re-enter a valid IP address.

**Error Handling:**

- The program includes robust error handling for incorrect IP address formats and invalid numeric ranges for each octet (0-255).
- An informative error message guides the user to enter a valid IPv4 address in the correct format.

**Example:**

- Input: `192.168.1.1`
- Output: 
  - Binary Format: `11000000 10101000 00000001 00000001`
  - Octal Format: `300.250.001.001`
  - Hex Format: `#c0a80101`
  - Decimal Format: `3232235777`
