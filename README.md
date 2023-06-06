# 14.7MapsAndSetsExercise

**Answer to quick question #1:
**[1, 2, 3, 4]

**Answer to quick question #2:
**ref

**Answer to quick question #3:
**[1, 2, 3] true
[1, 2, 3] false

**hasDuplicate function:**
function hasDuplicate(arr) {
  return new Set(arr).size !== arr.length;
  
hasDuplicate function using an arrow function:
const hasDuplicate = (arr) => new Set(arr).size !== arr.length;

**vowelCount function:**
function vowelCount(str) {
  const vowels = "aeiou";
  const countMap = new Map();
  
  for (let char of str.toLowerCase()) {
    if (vowels.includes(char)) {
      countMap.set(char, (countMap.get(char) || 0) + 1);
    }
  }
  
  return countMap;
}


  
  



