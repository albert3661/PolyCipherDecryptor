# PolyalphabeticCipher

## Description

PolyalphabeticCipher is a Python tool designed to decrypt text encoded with a polyalphabetic substitution cipher, such as the Caesar cipher. This script takes an input string and attempts to decode it by trying all possible key shifts (1 through 26) and outputs the resulting plaintext for each key.

## Features

- **Uniform Processing**: Converts the input text to lowercase for uniform processing.
- **Character Mapping**: Utilizes a character mapping based on shifted alphabet positions.
- **Handling Non-Alphabetic Characters**: Leaves non-alphabetic characters unchanged.
- **Comprehensive Output**: Outputs all possible plaintexts for each key shift, allowing the user to identify the correct key and deciphered text.

## Example

### Input
Copier cette commande dans un shell

`Grfg zrffntr`

### Output
```
Key 1: fqef yqeemsq
Key 2: epde xpdellr
Key 3: docd wocdkkq
Key 4: cncb vncjjjp
Key 5: bmba umbiioo
Key 6: alab tlahhnn
Key 7: zkza skzggmm
Key 8: yjyz rjyffll
Key 9: xixy qixeekk
Key 10: whwx phdddjj
Key 11: vgvw ogcccii
Key 12: ufun nfbbbhh
Key 13: teto meaaagg
Key 14: sdsn ldzzzff
Key 15: rcsm kcyyyee
Key 16: qbrl jbxxxdd
Key 17: paqk iawwwcc
Key 18: ozpj hzvvvbb
Key 19: nooi gyuuuaa
Key 20: mnnn fxtttzz
Key 21: lmmm ewsssyy
Key 22: klll dvrrrxx
Key 23: jkkk cuqqqww
Key 24: ijjj btpppvv
Key 25: hiii asooouu
Key 26: ghhh zrnnttt
```

shell
Copier le code

## Usage

### Prerequisites
- Python 3.x

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/albert3661/PolyalphabeticCipher.git
Navigate to the project directory:
bash

Copier le code
`cd PolyalphabeticCipher`
Running the Script
Run the script with the encrypted text as input:

bash
Copier le code
`python polyalphabetic_cipher.py "Grfg zrffntr"`
Review the output and identify the correct plaintext.

License
This project is licensed under the MIT License. See the LICENSE file for details.

