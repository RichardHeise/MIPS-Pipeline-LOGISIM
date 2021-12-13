# Trabalho para Arquitetura de Computadores

- Esse trabalho utilizou-se de uma implementação de MIPS pré-feita, os créditos estão ao final.
- O objetivo desse trabalho foi implementar uma cache simples (com base nesse link: https://curtsinger.cs.grinnell.edu/teaching/2015F/CSC211L/labs/lab11/) L1 com 4 entradas e endereço de 8 bits, sendo 4 de tag, 2 de index e mais 2 de offset. 
- O trabalho inteiro foi feito no LOGISIM.
- Testes das instruções podem ser encontradas na pasta testes. A implementação foi feita no MIPS Pipeline.


Link para o MIPS: https://github.com/jsingh07/MIPS-Logisim
# MIPS-Logisim
Author Jagdeep Singh & Muhammed Shafiq

Emulating MIPs instructions in multicycle, single cycle and 5 staged pipeline  
Instructions must be given in HEX and converted to little endian 
Aside can be used to convert MIPS into Hex and then transfered over into little endian 
Aside can be found at
http://csiflabs.cs.ucdavis.edu/~ssdavis/50/

A mips instruction like 
add  $1, $1, $1
would come out in hex from aside as 
20082100
and must be put into a text file and loaded into the intruction memory as 
00210820

Using aside 
1)simply type the wanted instruction and make sure CPU is set to MIPS
2)hit assemble found in the toolbar right side next to CPU (black button)
2)Open the .obj file with a text editor to read HEX instruction

Loading Instruciton
1) Simply right click the instruction ROM (usually the left most ROM)
2) hit load and select intruction file
