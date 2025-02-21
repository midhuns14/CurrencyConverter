Instructions:-
1.Open Eclipse
2.Run CurrencyConverterApplication.java
3.Open POSTMAN
4.Run GET mapping using this url:- localhost:8080/api/rates?base=USD  
 This will provide the exact convertion rate od USD to various currencies.
 5. Run POST mapping  with this url:- localhost:8080/api/convert   
 along with this url in "body" switch on "raw" and "Json"  and type 
 {
  "from": "INR",
  "to": "USD",
  "amount": 100
} 
in this format  to  convert currency from one to another.
