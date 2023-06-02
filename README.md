# Day 2 Super Powers

## Super Powers

In this activity, you will learn about coordinates and variables by helping Sensei make code that gives us super powers!

## Listen to Sensei

Make sure you are listening to Sensei and following along with the code!

## All Done!

Good work following along with Sensei!

```blocks
let speed = 1

player.onChat("jump", function () {
    player.teleport(pos(0, speed, 0))
})

player.onChat("zoom", function () {
    player.teleport(pos(0, 0, speed))
})

player.onChat("xoom", function () {
    player.teleport(pos(speed, 0, 0))
})

player.onChat("setSpeed", function (num1) {
    speed = num1;
})

player.onChat("randomSpeed", function () {
    speed = randint(2, 15);
})

player.onChat("return", function () {
    player.teleport(world(0, 0, 0))
})
```

## Activity Complete!

You did it! You learned about Variables and Coordinates in Minecraft!
