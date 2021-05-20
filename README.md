var radius;
var circ;
var points;
var length2;
var i;
var sides;
var repeat;

function draw_a_circle(radius) {
  circ = 2 * (3.14 * radius);
  for (var count = 0; count < 180; count++) {
      moveForward(circ / 180);
    turnLeft(2);
  }
}

/*
draw_a_circle(null);
moveBackward(20);
*/

/*
drawSticker('Dog',12);
*/

/*
for (i = 25; i >= 1; i -= 123) {
  length2 = circ;
}
*/
