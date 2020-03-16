**Abecedario en minusculas**

ABCL -> [q|w|e|r|t|y|u|i|o|p|a|s|d|f|g|h|j|k|l|z|x|c|v|b|n|m]

**Abecedario en mayusculas**

ABCH -> [Q|W|E|R|T|Y|U|I|O|P|A|S|D|F|G|H|J|K|L|Z|X|C|V|B|N|M]

**Numeros**

NUME -> [1|2|3|4|5|6|7|8|9|0]

**Caracteres alfanumericos**

ALFA -> [<ABCL>* | <ABCH>* | <NUME>*]

**Archivo**

ARCH -> (<ALFA>* . <ALFA>*)

**Tipos**

TYPE -> ('entero' | 'boleano' | 'cadena' | 'real')



## Constantes

CONST ->  (const <TYPE> = [<NUME>* | <ALFA>* | (<NUME>*.<NUME>*)])

## Identificadores

VARI -> (var <TYPE> = [<NUME>* | <ALFA>* | (<NUME>*.<NUME>*)])



## Operadores

**Operadores de relacion**

RELA -> [>|<|>=|<=|<>|==]

**Operadores logicos**

LOGI -> [AND|OR|NOT]

**Operadores aritméticos**

ARIT -> [+|-|*|^|%|/]

**Expresión boleana**

BOOL -> [(<VARI>  <RELA> <VARI>) | <LOGI>)*]



## Caracteres especiales

**Caracteres especiales**

CARC -> [!|@|#|$|%|^|&|*|(|)|'|;|,|/|\|?]

## Cadenas

**Cadenas**

CADE -> ("[<ALFA>* | <CARAC>]")

## Comentarios

**Comentario de linea simple**

CMM1 -> (/* <ALFA>*  */)

