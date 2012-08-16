microtext.js
=========

A micro JavaScript utility for processing text. Currently with only six functions.

Note: this library is only beginning and the author intends to make a great set of text utilities within it yet. Keep up.

Usage
-----

### Microtext object functions:

```javascript

Microtext.breakSentence("Gaal Dornick"); // ["Gaal", "Dornick"]

Microtext.truncate("Lewis Pirenne", 10) // "Lewis Pire..."

Microtext.abbrevName("Hari Seldon"); // "Hari S."

Microtext.firstName("Lors Avakim"); // "Lors"

Microtext.lastName("Salvor Hardin"); // "Hardin"

Microtext.getInitials("Bor Alurin"); // "B. A"

```

### String instance methods

```javascript

"Anselm haut Rodric".nameAt(2) // "Rodric"
"Anselm haut Rodric".nameAt(3) // undefined

```

### Auhor

  * Rodrigo Alves Vieira - rodrigovieira1994 [at] gmail [dot] com - http://www.rodrigoalvesvieira.com

Licence
-------

Copyright (c) 2012 Rodrigo Alves Vieira. http://www.rodrigoalvesvieira.com/

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to use, copy and modify copies of the Software, subject 
to the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.