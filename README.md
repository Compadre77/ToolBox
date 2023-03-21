# IDE Tipps
###Inline Refactoring mit:
‘ctrl’ + ‘alt’ + ‘n’
Dabei werden Variablen, die einmalig Konstant gesetzt wurden, überall im Code geändert. (Formulierung nicht ganz korrekt, aber man weiss was gemeint ist.)
/**
* Wenn man das 'x' mit der Maus markiert, und dann 'ctrl' + 'alt' + 'n' und mit 'ENTER' bestätigt, dann verschwindet 'const x = 1; und es steht nur noch 'const y = 1 * 2;'
* @type {number}
*/
const x = 1;       //verschwindet nach 'ctrl' + 'alt' + 'n'
const y = x * 2;   //wird zu const y = 1 * 2;