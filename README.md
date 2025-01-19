# Portfolio
def project1_catalog():  	# definition.
    item1_cost = 200000.0  	#Assigning price (500) to variable name item1.
    item2_cost = 5000.0  	#Assigning price (350) to variable name item2.
    item3_cost = 100000.0 	#Assigning price (1000) to variable name item3.
    combo1_cost = item1_cost + item2_cost - 0.1*(item1_cost + item2_cost)        #Computing the the price of Combo1.
    combo2_cost = item2_cost + item3_cost - 0.1*(item2_cost + item3_cost)        #Computing the the price of Combo2.
    combo3_cost = item1_cost + item3_cost - 0.1*(item1_cost + item3_cost)       #Computing the the price of Combo3.
    gift_pack_cost = item1_cost + item2_cost + item3_cost - 0.25*(item1_cost + item2_cost + item3_cost) 					#Computing the the price of Combo4.

    print("———————————————————————————————————————————————")   #Draws a line on the terminal.
    print("AN IMPACT POINTS GLOBAL VENTURE'S CATALOG")                        #Display the statement in quotation.
    print("-----------------------------------------------")   #Prints the dotted line.
    print("Product(s)                       Price")            #Print Product(s) and Price as the heading.
    print("Item 1: Laptop                 ", item1_cost)   #Display item1 and its price.
    print("Item 2: Flash                  ", item2_cost)   #Display item2 and its price.
    print("Item 3: Printer                ", item3_cost)   #Display item3 and its price.
    print("\n")
# If a customer purchases a combo pack with two unique items, he gets a 10% discount.  
# If the customer purchases a gift pack, he gets a 25% discount. 
    print("Combo 1 (Item 1 + 2)            ", combo1_cost)  #Display the result of combo1.
    print("Combo 2 (Item 2 + 3)            ", combo2_cost)  #Display the result of combo2.
    print("Combo 3 (Item 1 + 3)            ", combo3_cost)  #Display the result of combo3.
    print(f"Combo 4 (Item 1 + 2 + 3)         {gift_pack_cost}") #Display the result of combo4.
    print("————————————————————————————————————————————————")       #Draws a line at the bottom.
    print("Contact +2347061040400 for delivery")            #Print the statement in quotation.

project1_catalog() # Calling the function to print the catalog
