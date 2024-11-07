# Noisy simulation using Draper adder.


This tasks deals with the potrayal of increasing noise to the results. For these purposes of noise simulation I was required to build a adder circuit using the Draper algorithm. The drpaer algorithm achieves it using $|a,b\rangle \rightarrow^{Draper} |a,b+a\rangle$ using $|a,b\rangle \rightarrow^{QFT} |a,\phi(b)\rangle \rightarrow^{QFT} |a,\phi(a+b)\rangle \rightarrow^{IQFT} |a,a+b\rangle$