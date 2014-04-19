lpc_part_ids automatically extracts part IDs from NXP user manuals for LPC
microcontrollers that have previously been converted to text format using pdftotext.

Usage
-----


    > pdftotext UM10462.pdf
    > lpc_part_ids UM10462.txt
      #define LPC11U12_201_1 0x095C802B
      [...]
      #define LPC11U37_501   0x00007C40

