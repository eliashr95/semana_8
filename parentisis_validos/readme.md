function validParentheses(parens) {
  let valid = 0;
  for (let i = 0; i < parens.length; i++) {
    if (parens[i] === ')') valid--;
    if (parens[i] === '(') valid++;
    if (valid < 0) return false;
  }
  return valid == 0;
}
