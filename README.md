THIS IS A RANDOM JOKE GENERATOR CREATED USING SIMPLE HTML, CSS, JAVASCRIPT.

<h1>YOU CAN TRY THIS !</h1>




<!-- THIS IS CREATED BY AAKIDUL  -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome ! </title>
</head>
<body>
  <h1 class="X1">RANDOM JOKE GENERATOR</h1>
  <div class="container">
  <button class="generate_joke" onclick="jokeGenerate()">GENERATE</button>
  </div>
    
  </body>

<script>
function jokeGenerate() {
  const jokes = [
    "Why don’t scientists trust atoms? Because they make up everything!",
    "What do you call fake spaghetti? An impasta!",
    "Why did the scarecrow win an award? Because he was outstanding in his field!",
    "How do you organize a space party? You planet!",
    "Why did the bicycle fall over? It was two-tired!",
    "What do you call cheese that isn’t yours? Nacho cheese!",
    "Why don’t programmers like nature? It has too many bugs.",
    "What’s orange and sounds like a parrot? A carrot!",
    "Why did the math book look sad? Because it had too many problems.",
    "What do you get when you cross a snowman and a vampire? Frostbite!",
    "Why don’t skeletons fight each other? They don’t have the guts.",
    "How does a penguin build its house? Igloos it together!",
    "Why did the golfer bring two pairs of pants? In case he got a hole in one.",
    "What do you call an alligator in a vest? An investigator!",
    "Why was the math teacher suspicious of the calculator? It was up to something.",
    "What do you call a pile of cats? A meowtain!",
    "Why did the coffee file a police report? It got mugged!",
    "How does a lion greet the other animals in the field? “Pleased to eat you!”",
    "Why can’t you hear a pterodactyl go to the bathroom? Because the “P” is silent.",
    "What’s a skeleton’s least favorite room in the house? The living room!",
    "What did one wall say to the other wall? “I’ll meet you at the corner.”",
    "How does a cucumber become a pickle? It goes through a jarring experience!",
    "Why don’t some couples go to the gym? Because some relationships don’t work out.",
    "What’s the best thing about Switzerland? I don’t know, but the flag is a big plus.",
    "How do you catch a squirrel? Climb a tree and act like a nut!"
];

  const randomIndex = Math.floor(Math.random() * jokes.length);
    alert(jokes[randomIndex])
  
  
}

</script>

<style>
body {
  background-color: #124752;
  color: white;
}

.generate_joke {
  background-color: green;
  border-radius: 10px;
  border-color: black;
  
}
.container{
  text-align: center;
}
h1 { 
  text-align: center;
}

</style>

</html>
