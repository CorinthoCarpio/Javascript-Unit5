# Javascript-Unit5
var user = prompt("You are about to run on a dead end. Do you TURN BACK or CONTINUE ON?").toUpperCase();

switch (user) {
//first case
    case 'TURN BACK':
        var weapons = prompt("Have you got your weapons with you (YES or NO)?").toUpperCase();
        var hands = prompt("Are you confident to fight even without your weapons?").toUpperCase();
    if (weapons === 'YES' || hands === 'YES') {
        console.log("Looks like your chances of defeating them is high!");
        } else {
        console.log("Oh no! You collected no weapons and you have no prior karate training? I'm afraid it's goodbye my friend!");
        }
        break;
        
//second case
    case'CONTINUE ON':
        var river = prompt("You're about to reach the dead end! To your right is a fast-flowing river! Can you swim (YES or NO)?").toUpperCase();
        var ability = prompt("Man looks like there are hungry crocodiles waiting for you! Are you still going to swim?").toUpperCase();
    if (river === 'YES' && ability === 'YES') {
        console.log("Awesome! I'm sure you can survive this challenge!");
        } else {
        console.log("Then turn to your left and go down the slippery terrain instead!");
        }
        break;
    default:
    console.log("I didn't understand your choice. Hit Run and try again, this time picking TURN BACK or CONTINUE ON!");
    break;
}
