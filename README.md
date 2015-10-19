# Punto-Q-5.109
Further Analysis
Q.5.109 Load and run the script fi le, ctl _sphere of Example 5.18.
% Script file: ctl _ sphere

figure(1)

[r,ang] = meshgrid(linspace(0,1,50),linspace(0,2*pi,50));

x = r.*cos(ang);

y = r.*sin(ang);

surf(x,y,r);axis equal

figure(2)

[a,b] = meshgrid(linspace(0,2*pi,50),-1:2:1);

x = cos(a);

y = sin(a);

surf(x,y,b)

axis equal

figure(3)

[c,d] = meshgrid(linspace(0,2*pi,50),linspace(0,pi,25));

x = cos(c).*sin(d);

y = sin(c).*sin(d);

z = cos(d);

surf(x,y,z)

axis equal
