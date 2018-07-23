# myset_foreach


var array = [1, 2, 3, 4, 5];
let counter = 0;

function foreach(arr){

while (counter < array.length){
arr[counter] = (arr[counter] + 1);
counter++;
}

console.log(arr);

}

foreach(array);
