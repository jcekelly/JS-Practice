// In this kata you will create a function that takes a list of non-negative integers and strings and returns a new list with the strings filtered out.



function filter_list(l) {
  // create new empty array
  let integersOnly = []
  // create loop to itirate over array
  for (let i = 0; i < l.length; i++){
    // check if value is a number
    if (typeof (l[i]) !== 'string'){
      // if value is number, add to the new array
    integersOnly.push(l[i])
    } 
  }
 return integersOnly
}  

filter_list([1,2,'a','b'])

// Optimized Solution 

function filter_list(l) {
  return l.filter(Number.isInteger);
}
