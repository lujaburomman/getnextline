📄 Get_Next_Line

Get_Next_Line is a C function that allows reading a file line by line from a given file descriptor. It is designed to handle input efficiently, reading only as much data as necessary to return each line.

🔹 Project Overview

The function returns a single line on each call, including the newline character if present.

Returns NULL when the end of file is reached or if an error occurs.

Works with files and standard input.

Handles variable buffer sizes defined at compile time (-D BUFFER_SIZE=n).

Efficient memory and buffer management using static variables.

⚡ Key Points

Must read the file incrementally, not all at once.

Must be able to handle multiple consecutive calls without restarting.

Forbidden: global variables, lseek(), and external libraries like libft.
