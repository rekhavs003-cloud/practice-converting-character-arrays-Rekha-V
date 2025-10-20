# practice-converting-character-arrays-Rekha-V
// Task 1: Decode the Following Reversed Messages

// Message 1
let message1 = " !yako eb ll'uoy dna ,gniog peeK !sgnittes fo yteirav a ni slliks gnidoc esu osla nac uoY !ti teg ll'uoy ,tsisrep uoy fi tub ,tsrif ta drah mees yam gnidoC";
let decoded1 = message1.split('').reverse().join('');
console.log(decoded1);

// Message 2
let message2 = "!ecitcarp htiw retteb teg ll‘uoy ,emit ekaT .tsrif ta drah leef lliw gnitirw edoc tuB";
let decoded2 = message2.split('').reverse().join('');
console.log(decoded2);

// Message 3
let message3 = "!elpoep rehto morf tnereffid on era uoy ,elbuort evah uoy fI .lanoisseforp a ekil leef ot evah t'nod uoY";
let decoded3 = message3.split('').reverse().join('');
console.log(decoded3);

// Message 4
let message4 = ".rettam llits yeht ,smargorp llams etirw ylno nac uoy fI .tnemom tcefrep eht rof tiaw t'noD .yadot trats tsuJ";
let decoded4 = message4.split('').reverse().join('');
console.log(decoded4);


// Task 2: Write your own reverse messages

// Original messages
let inspire1 = "Keep learning, every small step counts!";
let inspire2 = "Believe in yourself, you can do it!";
let inspire3 = "Never give up, progress takes time.";

// Reverse the messages using split, reverse, and join
let reversed1 = inspire1.split('').reverse().join('');
let reversed2 = inspire2.split('').reverse().join('');
let reversed3 = inspire3.split('').reverse().join('');

// Log reversed messages
console.log(reversed1);
console.log(reversed2);
console.log(reversed3);
