# hw1
Tingyu's homework

HW1 contains Tingyu Hsiao (Bruce)'s first week homework. The four experiments I had are about giving various qualities to the bubbles generated by the bubble code provided by Michale.

Through changing certain value in each bracket, I successfully manipulated the fllowing qualities:

    1. The size of the bubbles:
Huge bubble: change “radius: random (50, 100)” (line10) to “radius: (800)”
Tiny bubble: change “radius:(50, 100)” (line10) to “radius: (200)”

    2. How vigorous the bubbles' motions are:
Vigorous bubbles: change “bubble.x += random(-1.1)” (line32) to “bubble.x += random(-100.100)”

    3. The color of the bubbles:
Neonblue bubbles: change line 28 to “fill(125, 220, 300, 255);” 

    4. The amount of the bubbles:
A lot of bubbles: change “for (var i = 0; i < 10; i++)” to “for (var i = 0; i < 300; i++)”
