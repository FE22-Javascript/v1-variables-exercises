# variables-exercises
variabler, datatyper och villkor

### Datatyper / variabler / villkor
**1** Vilka datatyper finns det i JS? Svara i form av en array.

```javascript
let datatypes = ['boolean', 'string', 'object', 'array', 'undefined', 'number' ]
```

**2** Är följande if sats *true* eller *false*?

```javascript
let a = 1;
let b = '1';
if(a == b) // true or false
```
Svar: true

**3** Vad är den *tekniska* skillnaden ( förutom var, let ) på dessa två deklarationer?

```javascript
let name = 'Greta Thunberg';
var name = 'Greta Thunberg';
```
Svar: var är funktions-scopead, medan let är block-scopead

**4.** Hur tar man reda på vad en variabel har för datatyp?

Svar: typeof

**5** Vilken av följande tecken visar ett ```kodblock```?

```javascript
[] // A 
() // B
{} // C <-
```

**6** Gör följande:

**6.1** Skapa variabeln my_num och tilldela den ett nummer.

```javascript
let my_num = 0;
```

**6.2** Skapa variabeln my_bool och tilldela den en boolean.

```javascript
let my_bool = false;
```

**6.3** Skapa variabeln my_str och tilldela den en sträng.

```javascript
let my_string = 'Maja är bäst';
```

**7** Vad kommer följande villkor att skriva ut?

```javascript
if ("cat" === "dog") {

  var outcome = "if block";

} else {

  var outcome = "else block";

}
```
Svar: "else block"

**8** Vad kommer följande villkor att skriva ut?

```javascript 
if (10 > 5) {

  var outcome = "if block";

}
```

Svar: "if block"


**9** Vad kommer följande switch-sats skriva ut?

```
var grade='B';

var result;

switch(grade)

{
  case 'A':
          {
            result+="10";
            break;
          }

  case 'B':
          {
          result+=" 9";
          break;
          }

  case 'C':
          {
            result+=" 8";
            break;
          }
          
  default:
  result+=" 0";
}

document.write(result);
```
Svar: 'undefined 9'
