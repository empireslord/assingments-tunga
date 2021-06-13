## part-1
1. `2 == "2";` `true`
1. `2 === 2;` `true`
1. `10 % 3;` `1`
1. `true && false;` `false`
1. `false || true` `true`
1. `true || false` `true`

## Part-2
1. ### Question
let isLearning = true;
if(isLearning){
    console.log("Keep it up!");
} else {
    console.log("Pretty sure you are learning....");
}
1. It will `console.log` "keep it up".
1. We use `if(isLearning === true)` because we know its a truthy valus=e so we allow the `if` statemw=ent turn it into a value that is `true` or `false`
    1. `if(isLearning)` will work cause it is a truthy statement.
1. ### Question2
let firstvariable;
let secondvariable = "";
let thirdvariable = 1;
let secretMessage = "Shh!";

if(firstvariable){
    console.log("first");
} else if(firstvariable || secondvariable){
    console.log("second");
} else if(firstvariable || thirdvariable){
    console.log("third");
} else {
    console.log("fourth");
}
1. It will console.log `third` cause its a truthy value.
1. The value of the first variable when initialized is `undefined`.
1. No its not cause its `undefined`.
1. no its not cause its an empty sting i.e `null`
1. The value of the third varaible is truthy because it has been defined as `1`.

## part-3
