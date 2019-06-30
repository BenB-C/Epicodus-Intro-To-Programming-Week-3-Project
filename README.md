# _Beep Boop_
[https://benjbc.github.io/epicodus/week3/beep-boop/](https://benjbc.github.io/epicodus/week3/beep-boop/)

#### _A web application that takes a number from a user and returns a range of numbers from 0 to the user inputted number, but with certain numbers replaced with special text, 2019.06.14_

#### By _**Benjamin Bennett-Cauchon**_

## Description

_This application takes a number from a user and returns a range of numbers from 0 to the user inputted number with the following exceptions:

* Numbers that contain a 1: all digits are replaced (all digits) with "Beep!"
* Numbers that contain a 2: all digits are replaced (all digits) with "Boop!"
* Numbers that contain a 3: all digits are replaced (all digits) with "I'm sorry, Dave. I'm afraid I can't do that."

These exceptions are written from least to most important. The first exception should apply unless the second exception does, and the same with the second and third. So, for example:

* The number 13 will be replaced with "I'm sorry, Dave. I'm afraid I can't do that."
* The number 21 will be replaced with "Boop".
* The number 32 will be replaced with "I'm sorry, Dave. I'm afraid I can't do that."

A user will be able to enter a new number and see new results over and over again._

## Setup/Installation Requirements

* _This is a single page web application without any special setup or installation requirements_

## Specs
| Behavior | Input | Output |
| ------------- |:-------------:| -----:|
| The program returns a range of numbers from 0 to the users inputted number | 0 | 0 |
| For numbers that contain a 1, all digits are replaced with "Beep!" | 1 | 0, "Beep!" |
| For numbers that contain a 2, all digits are replaced with "Boop!" | 2 | 0, "Beep!", "Boop!" |
| For numbers that contain a 3, all digits are replaced (all digits) with "I'm sorry, Dave. I'm afraid I can't do that." | 3 | 0, "Beep!", "Boop!", "I'm sorry, Dave. I'm afraid I can't do that." |
| The exception for numbers containing a 2 takes precedence over the exceptions for numbers containing a 1. | 12 | 0, "Beep!", "Boop!", "I'm sorry Dave...", 4, 5, 6, 7, 8, 9, "Beep!", "Beep!", "Boop!" |
| The exception for numbers containing a 3 takes precedence over the exceptions for numbers containing a 1 or 2. | 23 | 0, "Beep!", "Boop!", "I'm sorry Dave...", 4, 5, 6, 7, 8, 9, "Beep!", "Beep!", "Boop!", "I'm sorry Dave...", "Beep!", "Beep!", "Beep!", "Beep!", "Beep!", "Beep!", "Boop!", "Boop!", "Boop!", "I'm sorry Dave..." |

## Known Bugs

_There are no known bugs at this time. If you find one please email the author at Benjamin.BennettCauchon@gmail.com_

## Support and contact details

_If you find a bug, run into any issues, or have questions, ideas or concerns please feel free to email me at Benjamin.BennettCauchon@gmail.com or contact me through GitHub (user BenjBC)._

## Technologies Used

* Bootstrap
* JavaScript
  * document.getElementById()
  * element.focus()
  * element.scrollIntoView()
* jQuery

### License

MIT License

Copyright (c) 2019 Benjamin Bennett-Cauchon

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
