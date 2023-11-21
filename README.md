num = [0.3141 0.0687 0.00252];
den = [1 0.21];
G = tf(num, den)
bode(G), grid
margin(G)
