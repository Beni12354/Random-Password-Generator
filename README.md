import random
import time

print("Random Password Creator\nNOTE: If you enter 1 that means that it could have what you want. It does not mean that it will have it.")
data = 0
sym = 0
cap = 0
nums = 0
regular = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m']
r = random.randint(0,25)

regular2 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m']
r2 = random.randint(0,25)

regular3 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m']
r3 = random.randint(0,25)

regular4 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m']
r4 = random.randint(0,25)

regular5 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m']
r5 = random.randint(0,25)

regular6 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m']
r6 = random.randint(0,25)

regular7 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m']
r7 = random.randint(0,25)

regular8 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m']
r8 = random.randint(0,25)

regular9 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m']
r9 = random.randint(0,25)

regular10 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m']
r10 = random.randint(0,25)

regular11 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m']
r11 = random.randint(0,25)

regular12 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m']
r12 = random.randint(0,25)

regular13 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m']
r13 = random.randint(0,25)

regular14 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m']
r14 = random.randint(0,25)

regular15 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m']
r15 = random.randint(0,25)

num = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','1','2','3','4','5','6','7','8','9','0']
n = random.randint(0,35)

num2 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','1','2','3','4','5','6','7','8','9','0']
n2 = random.randint(0,35)

num3 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','1','2','3','4','5','6','7','8','9','0']
n3 = random.randint(0,35)

num4 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','1','2','3','4','5','6','7','8','9','0']
n4 = random.randint(0,35)

num5 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','1','2','3','4','5','6','7','8','9','0']
n5 = random.randint(0,35)

num6 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','1','2','3','4','5','6','7','8','9','0']
n6 = random.randint(0,35)

num7 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','1','2','3','4','5','6','7','8','9','0']
n7 = random.randint(0,35)

num8 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','1','2','3','4','5','6','7','8','9','0']
n8 = random.randint(0,35)

num9 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','1','2','3','4','5','6','7','8','9','0']
n9 = random.randint(0,35)

num10 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','1','2','3','4','5','6','7','8','9','0']
n10 = random.randint(0,35)

num11 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','1','2','3','4','5','6','7','8','9','0']
n11 = random.randint(0,35)

num12 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','1','2','3','4','5','6','7','8','9','0']
n12 = random.randint(0,35)

num13 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','1','2','3','4','5','6','7','8','9','0']
n13 = random.randint(0,35)

num14 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','1','2','3','4','5','6','7','8','9','0']
n14 = random.randint(0,35)

num15 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','1','2','3','4','5','6','7','8','9','0']
n15 = random.randint(0,35)

symb = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','!','@','#','$','?','^','&','*']
s = random.randint(0,33)

symb2 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','!','@','#','$','?','^','&','*']
s2 = random.randint(0,33)

symb3 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','!','@','#','$','?','^','&','*']
s3 = random.randint(0,33)

symb4 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','!','@','#','$','?','^','&','*']
s4 = random.randint(0,33)

symb5 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','!','@','#','$','?','^','&','*']
s5 = random.randint(0,33)

symb6 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','!','@','#','$','?','^','&','*']
s6 = random.randint(0,33)

symb7 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','!','@','#','$','?','^','&','*']
s7 = random.randint(0,33)

symb8 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','!','@','#','$','?','^','&','*']
s8 = random.randint(0,33)

symb9 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','!','@','#','$','?','^','&','*']
s9 = random.randint(0,33)

symb10 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','!','@','#','$','?','^','&','*']
s10 = random.randint(0,33)

symb11 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','!','@','#','$','?','^','&','*']
s11 = random.randint(0,33)

symb12 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','!','@','#','$','?','^','&','*']
s12 = random.randint(0,33)

symb13 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','!','@','#','$','?','^','&','*']
s13 = random.randint(0,33)

symb14 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','!','@','#','$','?','^','&','*']
s14 = random.randint(0,33)

symb15 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','!','@','#','$','?','^','&','*']
s15 = random.randint(0,33)

cappp = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M']
c = random.randint(0,51)

cappp2 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M']
c2 = random.randint(0,51)

cappp3 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M']
c3 = random.randint(0,51)

cappp4 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M']
c4 = random.randint(0,51)

cappp5 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M']
c5 = random.randint(0,51)

cappp6 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M']
c6 = random.randint(0,51)

cappp7 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M']
c7 = random.randint(0,51)

cappp8 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M']
c8 = random.randint(0,51)

cappp9 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M']
c9 = random.randint(0,51)

cappp10 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M']
c10 = random.randint(0,51)

cappp11 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M']
c11 = random.randint(0,51)

cappp12 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M']
c12 = random.randint(0,51)

cappp13 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M']
c13 = random.randint(0,51)

cappp14 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M']
c14 = random.randint(0,51)

cappp15 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M']
c15 = random.randint(0,51)


CapSym = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','!','@','#','$','?','^','&','*']
cs = random.randint(0,59)

CapSym2 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','!','@','#','$','?','^','&','*']
cs2 = random.randint(0,59)

CapSym3 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','!','@','#','$','?','^','&','*']
cs3 = random.randint(0,59)

CapSym4 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','!','@','#','$','?','^','&','*']
cs4 = random.randint(0,59)

CapSym5 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','!','@','#','$','?','^','&','*']
cs5 = random.randint(0,59)

CapSym6 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','!','@','#','$','?','^','&','*']
cs6 = random.randint(0,59)

CapSym7 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','!','@','#','$','?','^','&','*']
cs7 = random.randint(0,59)

CapSym8 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','!','@','#','$','?','^','&','*']
cs8 = random.randint(0,59)

CapSym9 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','!','@','#','$','?','^','&','*']
cs9 = random.randint(0,59)

CapSym10 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','!','@','#','$','?','^','&','*']
cs10 = random.randint(0,59)

CapSym11 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','!','@','#','$','?','^','&','*']
cs11 = random.randint(0,59)

CapSym12 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','!','@','#','$','?','^','&','*']
cs12 = random.randint(0,59)

CapSym13 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','!','@','#','$','?','^','&','*']
cs13 = random.randint(0,59)

CapSym14 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','!','@','#','$','?','^','&','*']
cs14 = random.randint(0,59)

CapSym15 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','!','@','#','$','?','^','&','*']
cs15 = random.randint(0,59)

CapSymNum = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','!','@','#','$','?','^','&','*','1','2','3','4','5','6','7','8','9','0']
csn = random.randint(0,69)

CapSymNum2 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','!','@','#','$','?','^','&','*','1','2','3','4','5','6','7','8','9','0']
csn2 = random.randint(0,69)

CapSymNum3 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','!','@','#','$','?','^','&','*','1','2','3','4','5','6','7','8','9','0']
csn3 = random.randint(0,69)

CapSymNum4 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','!','@','#','$','?','^','&','*','1','2','3','4','5','6','7','8','9','0']
csn4 = random.randint(0,69)

CapSymNum5 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','!','@','#','$','?','^','&','*','1','2','3','4','5','6','7','8','9','0']
csn5 = random.randint(0,69)

CapSymNum6 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','!','@','#','$','?','^','&','*','1','2','3','4','5','6','7','8','9','0']
csn6 = random.randint(0,69)

CapSymNum7 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','!','@','#','$','?','^','&','*','1','2','3','4','5','6','7','8','9','0']
csn7 = random.randint(0,69)

CapSymNum8 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','!','@','#','$','?','^','&','*','1','2','3','4','5','6','7','8','9','0']
csn8 = random.randint(0,69)

CapSymNum9 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','!','@','#','$','?','^','&','*','1','2','3','4','5','6','7','8','9','0']
csn9 = random.randint(0,69)

CapSymNum10 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','!','@','#','$','?','^','&','*','1','2','3','4','5','6','7','8','9','0']
csn10 = random.randint(0,69)

CapSymNum11 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','!','@','#','$','?','^','&','*','1','2','3','4','5','6','7','8','9','0']
csn11 = random.randint(0,69)

CapSymNum12 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','!','@','#','$','?','^','&','*','1','2','3','4','5','6','7','8','9','0']
csn12 = random.randint(0,69)

CapSymNum13 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','!','@','#','$','?','^','&','*','1','2','3','4','5','6','7','8','9','0']
csn13 = random.randint(0,69)

CapSymNum14 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','!','@','#','$','?','^','&','*','1','2','3','4','5','6','7','8','9','0']
csn14 = random.randint(0,69)

CapSymNum15 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','!','@','#','$','?','^','&','*','1','2','3','4','5','6','7','8','9','0']
csn15 = random.randint(0,69)

NumSym = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','!','@','#','$','?','^','&','*','1','2','3','4','5','6','7','8','9','0']
ns = random.randint(0,43)

NumSym2 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','!','@','#','$','?','^','&','*','1','2','3','4','5','6','7','8','9','0']
ns2 = random.randint(0,43)

NumSym3 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','!','@','#','$','?','^','&','*','1','2','3','4','5','6','7','8','9','0']
ns3 = random.randint(0,43)

NumSym4 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','!','@','#','$','?','^','&','*','1','2','3','4','5','6','7','8','9','0']
ns4 = random.randint(0,43)

NumSym5 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','!','@','#','$','?','^','&','*','1','2','3','4','5','6','7','8','9','0']
ns5 = random.randint(0,43)

NumSym6 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','!','@','#','$','?','^','&','*','1','2','3','4','5','6','7','8','9','0']
ns6 = random.randint(0,43)

NumSym7 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','!','@','#','$','?','^','&','*','1','2','3','4','5','6','7','8','9','0']
ns7 = random.randint(0,43)

NumSym8 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','!','@','#','$','?','^','&','*','1','2','3','4','5','6','7','8','9','0']
ns8 = random.randint(0,43)

NumSym9 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','!','@','#','$','?','^','&','*','1','2','3','4','5','6','7','8','9','0']
ns9 = random.randint(0,43)

NumSym10 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','!','@','#','$','?','^','&','*','1','2','3','4','5','6','7','8','9','0']
ns10 = random.randint(0,43)

NumSym11 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','!','@','#','$','?','^','&','*','1','2','3','4','5','6','7','8','9','0']
ns11 = random.randint(0,43)

NumSym12 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','!','@','#','$','?','^','&','*','1','2','3','4','5','6','7','8','9','0']
ns12 = random.randint(0,43)

NumSym13 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','!','@','#','$','?','^','&','*','1','2','3','4','5','6','7','8','9','0']
ns13 = random.randint(0,43)

NumSym14 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','!','@','#','$','?','^','&','*','1','2','3','4','5','6','7','8','9','0']
ns14 = random.randint(0,43)

NumSym15 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','!','@','#','$','?','^','&','*','1','2','3','4','5','6','7','8','9','0']
ns15 = random.randint(0,43)

CapNum = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','1','2','3','4','5','6','7','8','9','0']
cn = random.randint(0,61)

CapNum2 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','1','2','3','4','5','6','7','8','9','0']
cn2 = random.randint(0,61)

CapNum3 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','1','2','3','4','5','6','7','8','9','0']
cn3 = random.randint(0,61)

CapNum4 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','1','2','3','4','5','6','7','8','9','0']
cn4 = random.randint(0,61)

CapNum5 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','1','2','3','4','5','6','7','8','9','0']
cn5 = random.randint(0,61)

CapNum6 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','1','2','3','4','5','6','7','8','9','0']
cn6 = random.randint(0,61)

CapNum7 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','1','2','3','4','5','6','7','8','9','0']
cn7 = random.randint(0,61)

CapNum8 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','1','2','3','4','5','6','7','8','9','0']
cn8 = random.randint(0,61)

CapNum9 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','1','2','3','4','5','6','7','8','9','0']
cn9 = random.randint(0,61)

CapNum10 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','1','2','3','4','5','6','7','8','9','0']
cn10 = random.randint(0,61)

CapNum11 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','1','2','3','4','5','6','7','8','9','0']
cn11 = random.randint(0,61)

CapNum12 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','1','2','3','4','5','6','7','8','9','0']
cn12 = random.randint(0,61)

CapNum13 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','1','2','3','4','5','6','7','8','9','0']
cn13 = random.randint(0,61)

CapNum14 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','1','2','3','4','5','6','7','8','9','0']
cn14 = random.randint(0,61)

CapNum15 = ['q','w','e','r','t','y','u','i','o','p','a','s','d','f','g','h','j','k','l','z','x','c','v','b','n','m','Q','W','E','R','T','Y','U','I','O','P','A','S','D','F','G','H','J','K','L','Z','X','C','V','B','N','M','1','2','3','4','5','6','7','8','9','0']
cn15 = random.randint(0,61)

#symbols = !@#$?^&*

#print("")
# # = 3 | caps = 6 | symbols = 9 | characters = 1+
#print(" # | CAPS | symbols | characters\n1. |  no  |    no   | 8\n2. | ")
characters = input("1. 8 characters\n2. 10 characters\n3. 15 characters\n\nHow many characters would you like? 1/2/3 ")
if characters.lower() == '1':
  data = data + 1
  print('')

if characters.lower() == '2':
  data = data + 2
  print('')

if characters.lower() == '3':
  data = data + 3
  print('')

symbols = input("NOTE: Symbols include: !@#$?^&*\n Would you like symbols? 1 for yes/0 for no ")
if symbols.lower() == '1':
  sym = sym + 1
  print("")

if symbols.lower() == '0':
  sym = sym + 0
  print("")

caps = input("Would you like capital letter? 1 for yes/0 for no ")
if caps.lower() == '1':
  cap = cap + 1
  print("")

if caps.lower() =='0':
  cap = cap + 0
  print("")

numbers = input("Would you like numbers? 1 for yes/0 for no ")
if numbers.lower() == '1':
  nums = nums + 1
  print("")

if numbers.lower() == '0':
  nums = nums + 0
  print("")

print("Creating your password please hang tight.")
time.sleep(1) 
print('')
if data == 1 and sym == 0 and cap == 0 and nums == 0:
  print("{}{}{}{}{}{}{}{}".format(regular2[r2],regular[r],regular3[r3],regular5[r5],regular4[r4],regular6[r6],regular8[r8],regular7[r7]))
  print("Reload the page to restart.")

if data == 1 and sym == 1 and cap == 0 and nums == 0:
  print("{}{}{}{}{}{}{}{}".format(symb[s],symb3[s3],symb2[s2],symb5[s5],symb4[s4],symb7[s7],symb6[s6],symb8[s8]))
  print("Reload the page to restart.")

if data == 1 and sym == 0 and cap == 0 and nums == 1:
  print("{}{}{}{}{}{}{}{}".format(num[n],num3[n3],num2[n2],num5[n5],num4[n4],num7[n7],num6[n6],num8[n8]))
  print("Reload the page to restart.")

if data == 1 and sym == 0 and cap == 1 and nums == 0:
  print("{}{}{}{}{}{}{}{}".format(cappp[c],cappp3[c3],cappp2[c2],cappp5[c5],cappp4[c4],cappp7[c7],cappp6[c6],cappp8[c8]))
  print("Reload the page to restart.")

if data == 1 and sym == 1 and cap == 1 and nums == 1:
  print("{}{}{}{}{}{}{}{}".format(CapSymNum[csn],CapSymNum3[csn3],CapSymNum2[csn2],CapSymNum5[csn5],CapSymNum4[csn4],CapSymNum7[csn7],CapSymNum6[csn6],CapSymNum8[csn8]))
  print("Reload the page to restart.")

if data == 1 and sym == 1 and cap == 1 and nums == 0:
  print("{}{}{}{}{}{}{}{}".format(CapSym[cs],CapSym3[cs3],CapSym2[cs2],CapSym5[cs5],CapSym4[cs4],CapSym7[cs7],CapSym6[cs6],CapSym8[cs8]))
  print("Reload the page to restart.")

if data == 1 and sym == 1 and cap == 0 and nums == 1:
  print("{}{}{}{}{}{}{}{}".format(NumSym[ns],NumSym3[ns3],NumSym2[ns2],NumSym5[ns5],NumSym4[ns4],NumSym7[ns7],NumSym6[ns],NumSym8[ns8]))

if data == 1 and sym == 0 and cap == 1 and nums == 1:
  print("{}{}{}{}{}{}{}{}".format(CapNum[cn],CapNum3[cn3],CapNum2[cn2],CapNum5[cn5],CapNum4[cn4],CapNum7[cn7],CapNum6[cn6],CapNum8[cn8]))
  print("Reload the page to restart.")



if data == 2 and sym == 0 and cap == 0 and nums == 0:
  print("{}{}{}{}{}{}{}{}{}{}".format(regular2[r2],regular[r],regular3[r3],regular5[r5],regular4[r4],regular6[r6],regular8[r8],regular7[r7],regular10[r10],regular9[r9]))
  print("Reload the page to restart.")

if data == 2 and sym == 1 and cap == 0 and nums == 0:
  print("{}{}{}{}{}{}{}{}{}{}".format(symb[s],symb3[s3],symb2[s2],symb5[s5],symb4[s4],symb7[s7],symb6[s6],symb8[s8],symb10[s10],symb9[s9]))
  print("Reload the page to restart.")

if data == 2 and sym == 0 and cap == 0 and nums == 1:
  print("{}{}{}{}{}{}{}{}{}{}".format(num[n],num3[n3],num2[n2],num5[n5],num4[n4],num7[n7],num6[n6],num8[n8],num10[n10]))
  print("Reload the page to restart.")

if data == 2 and sym == 0 and cap == 1 and nums == 0:
  print("{}{}{}{}{}{}{}{}{}{}".format(cappp[c],cappp3[c3],cappp2[c2],cappp5[c5],cappp4[c4],cappp7[c7],cappp6[c6],cappp8[c8],cappp10[c10],cappp9[c9]))
  print("Reload the page to restart.")

if data == 2 and sym == 1 and cap == 1 and nums == 1:
  print("{}{}{}{}{}{}{}{}{}{}".format(CapSymNum[csn],CapSymNum3[csn3],CapSymNum2[csn2],CapSymNum5[csn5],CapSymNum4[csn4],CapSymNum7[csn7],CapSymNum6[csn6],CapSymNum8[csn8],CapSymNum10[csn10],CapSymNum9[csn9]))
  print("Reload the page to restart.")

if data == 2 and sym == 1 and cap == 1 and nums == 0:
  print("{}{}{}{}{}{}{}{}{}{}".format(CapSym[cs],CapSym3[cs3],CapSym2[cs2],CapSym5[cs5],CapSym4[cs4],CapSym7[cs7],CapSym6[cs6],CapSym8[cs8],CapSym10[cs10],CapSym9[cs9]))
  print("Reload the page to restart.")

if data == 2 and sym == 1 and cap == 0 and nums == 1:
  print("{}{}{}{}{}{}{}{}{}{}".format(NumSym[ns],NumSym3[ns3],NumSym2[ns2],NumSym5[ns5],NumSym4[ns4],NumSym7[ns7],NumSym6[ns],NumSym8[ns8],NumSym10[ns10],NumSym9[ns9]))
  print("Reload the page to restart.")

if data == 2 and sym == 0 and cap == 1 and nums == 1:
  print("{}{}{}{}{}{}{}{}{}{}".format(CapNum[cn],CapNum3[cn3],CapNum2[cn2],CapNum5[cn5],CapNum4[cn4],CapNum7[cn7],CapNum6[cn6],CapNum8[cn8],CapNum10[cn10],CapNum9[cn9]))
  print("Reload the page to restart.")



if data == 3 and sym == 0 and cap == 0 and nums == 0:
  print("{}{}{}{}{}{}{}{}{}{}{}{}{}{}{}".format(regular2[r2],regular[r],regular3[r3],regular5[r5],regular4[r4],regular6[r6],regular8[r8],regular7[r7],regular10[r10],regular9[r9],regular12[r12],regular11[r11],regular14[r14],regular13[r13],regular15[r15]))
  print("Reload the page to restart.")

if data == 3 and sym == 1 and cap == 0 and nums == 0:
  print("{}{}{}{}{}{}{}{}{}{}{}{}{}{}{}".format(symb[s],symb3[s3],symb2[s2],symb5[s5],symb4[s4],symb7[s7],symb6[s6],symb8[s8],symb[s10],symb9[s9],symb12[s12],symb11[s11],symb14[s14],symb13[r13],symb15[s15]))
  print("Reload the page to restart.")

if data == 3 and sym == 0 and cap == 0 and nums == 1:
  print("{}{}{}{}{}{}{}{}{}{}{}{}{}{}{}".format(num[n],num3[n3],num2[n2],num5[n5],num4[n4],num7[n7],num6[n6],num8[n8],num10[n10],num9[n9],num12[n12],num11[n11],num14[n14],num13[n13],num15[n15]))
  print("Reload the page to restart.")

if data == 3 and sym == 0 and cap == 1 and nums == 0:
  print("{}{}{}{}{}{}{}{}{}{}{}{}{}{}{}".format(cappp[c],cappp3[c3],cappp2[c2],cappp5[c5],cappp4[c4],cappp7[c7],cappp6[c6],cappp8[c8],cappp10[c10],cappp9[c9],cappp12[c12],cappp11[c11],cappp14[c14],cappp13[c13],cappp15[c15]))
  print("Reload the page to restart.")

if data == 3 and sym == 1 and cap == 1 and nums == 1:
  print("{}{}{}{}{}{}{}{}{}{}{}{}{}{}{}".format(CapSymNum[csn],CapSymNum3[csn3],CapSymNum2[csn2],CapSymNum5[csn5],CapSymNum4[csn4],CapSymNum7[csn7],CapSymNum6[csn6],CapSymNum8[csn8],CapSymNum10[csn10],CapSymNum9[csn9],CapSymNum12[csn12],CapSymNum11[csn11],CapSymNum14[csn14],CapSymNum13[csn13],CapSymNum15[csn15]))
  print("Reload the page to restart.")

if data == 3 and sym == 1 and cap == 1 and nums == 0:
  print("{}{}{}{}{}{}{}{}{}{}{}{}{}{}{}".format(CapSym[cs],CapSym3[cs3],CapSym2[cs2],CapSym5[cs5],CapSym4[cs4],CapSym7[cs7],CapSym6[cs6],CapSym8[cs8],CapSym10[cs10],CapSym9[cs9],CapSym12[cs12],CapSym11[cs11],CapSym14[cs14],CapSym13[cs13],CapSym15[cs15]))
  print("Reload the page to restart.")

if data == 3 and sym == 1 and cap == 0 and nums == 1:
  print("{}{}{}{}{}{}{}{}{}{}{}{}{}{}{}".format(NumSym[ns],NumSym3[ns3],NumSym2[ns2],NumSym5[ns5],NumSym4[ns4],NumSym7[ns7],NumSym6[ns],NumSym8[ns8],NumSym10[ns10],NumSym9[ns9],NumSym12[ns12],NumSym11[ns11],NumSym14[ns14],NumSym13[ns13],NumSym15[ns15]))
  print("Reload the page to restart.")

if data == 3 and sym == 0 and cap == 1 and nums == 1:
  print("{}{}{}{}{}{}{}{}{}{}{}{}{}{}{}".format(CapNum[cn],CapNum3[cn3],CapNum2[cn2],CapNum5[cn5],CapNum4[cn4],CapNum7[cn7],CapNum6[cn6],CapNum8[cn8],CapNum10[cn10],CapNum9[cn9],CapNum12[cn12],CapNum11[cn11],CapNum14[cn14],CapNum13[cn13],CapNum15[cn15]))
  print("Reload the page to restart.")
#if data ==  and sym ==  and cap ==  and nums == :
  #print("{}{}{}{}{}{}{}{}".format())

#print("{}{}{}{}{}{}{}{}".format(regular2[r2],regular[r],regular3[r3],regular5[r5],regular4[r4],regular6[r6],regular8[r8],regular7[r7]))

