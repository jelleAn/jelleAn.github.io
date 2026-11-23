var ballx = 40; // width/2 ?
var bally = 40;
var ballSize = 10;
var score =0;
var img1, img2, img3, beginImg;
var  c; // our text color as a variable, set in setup
var gameState ="begin";

function preload() {
  img1 = loadImage("https://jellean.github.io/images/kirby_sleepy.png");
  img2 = loadImage("https://jellean.github.io/images/kirby.png");
  img3 = loadImage("https://jellean.github.io/images/kirby_watermelon.png");
}

function setup() {
  createCanvas(600, 600);
  c =color(255, 255, 255); //text color
  fill(c);
  textAlign(CENTER);
  textSize(20); 
} // end of setup

function draw() {

  if (gameState == "begin") {
    background(0);
    beginGame();

  } 
  if (gameState == "L1") {
    background(200, 100, 0);
    levelOne();

  } 
  if (gameState == "L2") {
    background(200, 100, 0);
    levelTwo();

  } 
  if (gameState == "L3") {
  background(0); // black background
  levelThree();

  } 
  if (gameState == "Win") {
    background(0);
    win();
  }

  text("Score: " + score, width / 2, 40);
}
function beginGame(){
 if (mouseIsPressed === true) {
  gameState="L1";  
 } // end of if mousIsPressed
} // end of beginGame


function levelOne(){
  text("level 1", width/2, height-20);
  var distToBall = dist(ballx+20, bally+20, mouseX, mouseY);
  if (distToBall<ballSize/.25){
    ballx= random(width-5);
    bally = random(height-5);
    score = score +1;
  } // end if
  if (score>=10){
    gameState= "L2";
  }
  line(ballx+20, bally+20, mouseX, mouseY);
image(img1, ballx-20, bally-20,160,80);
} // end of level 1


function levelTwo() {
  background(0);
  image(img1, ballx, bally, 160, 80);
  text("level 2", width/2, height-20);
  var distToBall = dist(ballx+20, bally+20, mouseX, mouseY);
  if (distToBall<ballSize/.25){
    ballx= random(width-5);
    bally = random(height-5);
    score = score +1;
    ballSize=ballSize-.1;
  } // end if
  if (score>=25){
       gameState= "L3";
  }
}

var kirbySize = 160;

function levelThree() {
  background(0);

  image(img3, ballx, bally, kirbySize, kirbySize / 2);

  if (dist(ballx + kirbySize / 2, bally + kirbySize / 4, mouseX, mouseY) < kirbySize / 2) {
    score++;
    ballx = random(width - kirbySize);
    bally = random(height - kirbySize / 2);
    kirbySize = max(50, kirbySize - 10);
  }
  
  if (score >= 40) {
    gameState = "Win";
  }
}
  function win() {
  background(img2);
  fill(255);
  textAlign(CENTER, CENTER);
  textSize(32);
  text("You Won!", width / 2, height / 2);
}
