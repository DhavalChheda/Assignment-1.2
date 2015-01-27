# Assignment-1.2
  smooth();
  noFill();
  strokeWeight(5);
  frameRate(5);
  background(255);
}

void draw(){
  float x = random(width);
  float y = random(height);
  float d = random(30, 300);
  stroke(random(255), random(255), random(255));
  ellipse(x, y, d, d);
}
