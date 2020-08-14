# Final_project
x = [0:1:125];
y = ((0.6+0.02+0.0015*x));
plot(x,y)
title('Efficiency vs P(in)');
xlabel('P(in)');
ylabel('Efficiency');

x = [25:1:100];
y = x/(298./(2.2)); 
plot(x, y)
title('Endurance vs Fuel Capacity');
xlabel('Fuel Capacity');
ylabel('Endurance');
