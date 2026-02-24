⚡ Most Important Interview Difference

| Type                 | Hoisted?      | Initialized? | Can call before declaration? |
| -------------------- | ------------- | ------------ | ---------------------------- |
| var                  | Yes           | undefined    | Yes (but undefined)          |
| let                  | Yes           | No           | No (TDZ error)               |
| const                | Yes           | No           | No (TDZ error)               |
| Function Declaration | Yes           | Fully        | Yes                          |
| Function Expression  | Variable only | undefined    | No                           |

var → hoisted + initialized (undefined)
let/const → hoisted but in TDZ
function declaration → fully hoisted
function expression → behaves like variable

Hoisting is JavaScript's behavior where variable and function declarations are moved to the top of their scope during the memory creation phase before code execution.  