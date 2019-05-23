print (''' HESAP MAKİNESİ

-----HOŞGELDİNİZ-----

     DARKIZM.ORG
=====================
1) TOPLAMA 
2) CIKARMA
3) CARPMA 
4) BÖLME  
=====================

''')
 
 veri = input (" işlem :")

 if veri =="1":
 	x = input ("ilk sayı .")
 	x = float (x)
 	y = input ("ilkinci sayı .")
 	y = float (y)
 	print ("sonuç:",x + y)

    elif veri == "2":
 	x = input ("ilk sayı .")
 	x = float (x)
 	y = input ("ilkinci sayı .")
 	y = float (y)
 	print ("sonuç:",x - y)

 	elif veri == "3":
    x = input ("ilk sayı .")
 	x = float (x)
 	y = input ("ilkinci sayı .")
 	y = float (y)
 	print ("sonuç:",x * y)

    elif veri == "4":
 	x = input ("ilk sayı .")
 	x = float (x)
 	y = input ("ilkinci sayı .")
 	y = float (y)
 	print ("sonuç:",x / y)
 	
 	else: 
 		print("Yanliş Secim :( program kapanıyor ... ")
 		quit()
