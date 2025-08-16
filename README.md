# Data types in C++

## The preface

See the detailed description on the website [metanit.com](https://metanit.com/cpp/tutorial/2.3.php)

## Data Type table

| *Logical type* | Range of values | Weight | Initialization example |
| -------------- | --------------- | ------ | ---------------------- |
| *bool* | **0** (false) or **1** (treu) | 1 byte (8 bits) | ```bool isAlive {true};```|

| *Integer types* | Range of values | Weight | Initialization example |
| --------------- | --------------- | ------ | ---------------------- |
| *signed char* | from -128 to 127 | 1 byte (8 bits) | ```signed char num{ -64 };``` |
| *unsigned char* | from 0 to 255 | 1 byte (8 bits) | ```unsigned char num{ 64 };``` |
| *char* | from -128 to 127, or from 0 to 255 | 1 byte (8 bits) | ```char sign{ 24 };``` |
| *short* | from -32768 to 32767 | 2 bytes (16 bits) | ```short num{ -88 };``` |
| *unsigned short* | from 0 to 65535 | 2 bytes (16 bits) | ```unsigned short num{ 88 };``` |
| *int* | from -32768 to 32767 | 2 bytes (16 bits) |  |
|  | from -2 147 483 648 to 2 147 483 647 | 4 bytes (32 bits) | ```int num{ -1024 };``` |
| *unsigned int* | from 0 to 65535 | 2 bytes (16 bits) |  |
|  | from 0 to 4 294 967 295 | 4 bytes (32 bits) | ```unsigned int num{ 1024 };``` |
| *long* |  from -2 147 483 648 to 2 147 483 647 | 4 bytes (32 bits) |  |
|  | from -9 223 372 036 854 775 808 to 9 223 372 036 854 775 807 | 8 bytes (64 bits) | ```long num{ -2048 };``` |
| *unsigned long* | from 0 to 4 294 967 295 | 4 bytes (32 bits) | ```unsigned long num{ 2048 };``` |
| *long long* | from -9 223 372 036 854 775 808 to 9 223 372 036 854 775 807 | 8 bytes (64 bits) | ```long long num{ -4096 };``` |
| *unsigned long long* | from 0 to 18 446 744 073 709 551 615 | 8 bytes (64 bits) | ```unsigned long long num{ 4096 };``` |

| *Floating point numbers* | Range of values | Weight | Initialization example |
| ------------------------ | --------------- | ------ | ---------------------- |
| *float* | from 3.4E-38 to 3.4E+38 | 4 bytes (32 bits) | ```float num{ 10.56f };``` |
| *double* | from 1.7E-308 to 1.7E+308 | 8 bytes (64 bits) | ```double num {10.45};``` |
| *long double* | from 3.36E–4932 to 3.16E+4932 | 16 bytes (128 bits) | ```double num2{ 1. };``` |

| *Character types* | Range of values | Weight | Encoding | Initialization example |
| ----------------- | --------------- | ------ | -------- | ---------------------- |
| *char* | from -128 to 127, or from 0 to 255 | 1 byte (8 bits) | ASCII | ```char a1 {'A'};``` |
| *wchar_t* | from 0 to 65 535 (Windows) | 2 bytes (16 bits) | Unicode |  |
|  | from 0 to 4 294 967 295 (Linux) | 4 bytes (32 bits) | Unicode | ```wchar_t a1 {L'A'};``` |
| *char8_t* | from 0 to 256 | 1 byte (8 bits) | Unicode | ```char8_t c{ u8'l' };``` |
| *char16_t* | from 0 to 65 535 | 2 bytes (16 bits) | Unicode | ```char16_t d{ u'l' };``` |
| *char32_t* | from 0 to 4 294 967 295 | 4 bytes (32 bits) | Unicode | ```char32_t e{ U'o' };``` |

| *The auto specifier* | Range of values | Weight | Encoding | Initialization example |
| -------------------- | --------------- | ------ | -------- | ---------------------- |
| *auto* | none | none | none | ```auto number = 5;``` |
