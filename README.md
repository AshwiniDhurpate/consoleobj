let obj1 = {
  value: "a"
}

let obj2 = {
  value: "b"
}

console.log(obj1.value)
console.log(obj2.value)


function change(obj1, obj2) {
  obj1 = obj2;
  obj2.value = "c";
  console.log(obj1.value)
  console.log(obj2.value)
}

change(obj1, obj2);

console.log(obj1.value)
console.log(obj2.value)
