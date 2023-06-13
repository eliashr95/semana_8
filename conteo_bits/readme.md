var countBits = function (n) {
  let binaryNumber = n.toString(2);
  let oneBitCount = 0;
  for (let i = 0; i < binaryNumber.length; i++) {
    if (binaryNumber[i] === '1') oneBitCount++;
  }
  return oneBitCount;
};
