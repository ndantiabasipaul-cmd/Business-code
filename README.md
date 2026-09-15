# Business-code
customer_purchase1=input()
price=5.00
amount=customer_purchase1*price
amount1=float(amount)
amount2=round(amount1, 2)
#condition: if customer buys more than 1
if customer_purchase1 >1:
    discount=(10/100)*amount2
    discount1=round(discount, 2)
    total1=amount2-discount1
if customer_purchase1 <2:
    discount=0.00
    total1=amount2-discount
tax=(7/100)*total1
tax1=round(tax, 2)
total2=total1+tax1
total3=float(total2)
total=round(total3, 2)
print(total)
