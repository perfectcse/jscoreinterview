let is block-scoped and can be updated but not re-declared.
let age = 22;
age = 23;      // ✅ allowed
// let age = 25; ❌ not allowed