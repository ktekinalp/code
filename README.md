// Move the mouse across the image
// to change its value
color[] colors = { #ffcc50, #ccff50, #07ffcc };

void setup() {
  size(500,500, OPENGL);
    background(159);
      translate(250,250);
      }
      
      float rotation = 0;
      void draw() {
        rotation+=0.01;
          rotateZ(rotation);
          }
          
          void mouseMoved() {
          
          
          
            rect(25, 25, 50, 50);
            }
            
