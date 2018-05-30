INPUT:files of sales records
output: sales tax report,customer name,purchaseAmount, taxcode
process

pseodocode

Read Sales_Records
IF Tax_code=0,
	Then Sales Tax= 0
Elseif Tax_code =1, Sales_tax =3/100
Elseif Tax_code =2, Sales_tax =5/100
Elseif Tax_code =3, Sales_tax =7/100
ENDIF
ENDIF
Tax Amount = Sales tax * Sales Amount
Total Amount =Tax Amount+Sales Amount
Print "Sales Report"
Print Customer_number, Customer_name, Sales_amount, Sales_tax, Total Amount
END

ProducSalesReport