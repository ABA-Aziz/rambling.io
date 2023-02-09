<!doctype html>
<html lang="en">
    <head>
        <meta charset="utf-8">
            <meta name="viewport" content="width = device-width, intial-scale = 1">
                <title>JavaScript Asteroids</title>
                <link rel="stylesheet" type="text/css" href="style.css"></link>
                <script src="asteroids.js"></script>
            </meta>
        </meta>
    </head>
</html>


<script>
  console.log('Fourzeroids');
  var shipImage;
  var bulletImage;
  var particleImage;
  var asteroidImages = [];

  function preload() {
      shipImage = loadImage('fourze.png');
      particleImage = loadImage('explosion.png');
      bulletImage = loadImage('drill.webp');
  }
  
  for (var i = 0; i < 3; i++){
                        var asteroidImage = loadImage('meteorRidewatch' + i +'.png')
                        asteroidImages.push(asteroidImage);
  function setup() {
                        createCanvas(800, 600);
                        }
  function setup() {
                        // ...
                        ship = createSprite(width/2, height/2);
                        ship.maxSpeed = 6;
                        ship.friction = 0.01;
                        ship.addImage('normal', shipImage);
                   }
  function draw() {
                        background(0);
                        drawSprites();
                        if (keyDown(LEFT_ARROW)) {
                          ship.rotation -= 4;
                        }
                        if (keyDown(RIGHT_ARROW)) {
                          ship.rotation += 4;
                        }
                        if (keyDown(UP_ARROW)) {
                          ship.addSpeed(0.35, ship.rotation);
                        }
                        if (keyWentDown('a')) {
                          var bullet = createSprite(ship.position.x, ship.position.y);
                          bullet.addImage(bulletImage);
                          bullets.add(bullet);
                          bullet.setSpeed(10 + ship.getSpeed(), ship.rotation);
                          bullet.life = 30;
                        }
  var asteroids;
  var bullets;
  function setup() {
                        asteroids = new Group();
                        bullets = new Group();

                        
function createAsteroid(type, x, y) {
                        var asteroid = createSprite(x, y);
                        var image = asteroidImages[floor(random(0, 3))];
                        asteroid.addImage(meteorRidewatch.png);
                        asteroid.setSpeed(2.5 - type / 2, random(360));
                        asteroid.rotationSpeed = 0.75;
                        asteroid.type = type;
                        
                        if (type === 2) {
                          asteroid.scale = 0.7;
                        }
                        
                        if (type === 1) {
                          asteroid.scale = 0.35;
                        }
                        
                        asteroid.mass = asteroid.scale + 2;
                        asteroid.setCollider('circle', 0, 0, 50);
                        asteroids.add(asteroid);
                        return asteroid;
                        
                        }
function setup() {
                        for (var i = 0; i < 8; i ++) {
                          var angle = random(360);
                          
  
  preload();
  
</script>
