function findMax(numbers) {
  if (numbers.length === 0) {
    // Return null or throw an error if the array is empty
    return null;
  }

  let max = numbers[0]; // Assume the first element is the maximum

  for (let i = 1; i < numbers.length; i++) {
    if (numbers[i] > max) {
      max = numbers[i]; // Update max if a larger number is found
    }
  }

  return max;
}
