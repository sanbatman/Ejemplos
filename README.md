N1 = raw_input("Dime el valor de uno ")
N2 = raw_input("Dime el valor de dos ")
N3 = raw_input("Dime el valor de tres ")

if N1 > N2:
  if N1 > N3:
    if N2 > N3:
    print str(N1)+ " - "+ str(N2)+ "-"+ str(N3)
	else:
	  print str(N1)+ " - "+ str(N3)+ "-"+ str(N2)
	  else:
	  print str(N3)+ " - "+ str(N1)+ "-"+ str(N2)
else:
  if N2 > N3:
    if N1 > N3:
	  print str(N2)+ " - "+ str(N1)+ "-"+ str(N3)
	else:
	  print str(N2)+ " - "+ str(N3)+ "-"+ str(N1)
	else:
	  print str(N3)+ " - "+ str(N2)+ "-"+ str(N1)
