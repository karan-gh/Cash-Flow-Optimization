# Cash-Flow-Optimization
The project is designed to minimize the number of financial transactions needed among multiple entities, either banks or individuals, to settle their debts. The primary goal is to reduce the complexity and number of transactions by optimizing how these debts are settled, considering constraints such as different payment modes for banks and all available payment methods for personal transactions.


for example, Following is the list of Banks and their supported payment modes :

Bank_of_America          -   Google_Pay, AliPay, Paytm
Wells_Fargo              -   Google_Pay, AliPay
Royal_Bank_of_Canada     -   AliPay
Westpac                  -   Google_Pay, Paytm
Goldman_Sachs            -   Paytm
National_Australia_Bank  -   AliPay, Paytm


Following are the payments to be done:
---------------------------------------------------------------------------------
Debtor Bank                   Creditor Bank                                Amount   
---------------------------------------------------------------------------------
Goldman_Sachs                 Bank_of_America                              Rs 100
Goldman_Sachs                 Wells_Fargo                                  Rs 300
Goldman_Sachs                 Royal_Bank_of_Canada                         Rs 100
Goldman_Sachs                 Westpac                                      Rs 100
National_Australia_Bank       Bank_of_America                              Rs 300
National_Australia_Bank       Royal_Bank_of_Canada                         Rs 100
Bank_of_America               Wells_Fargo                                  Rs 400
Wells_Fargo                   Royal_Bank_of_Canada                         Rs 200
Royal_Bank_of_Canada          Westpac                                      Rs 500
---------------------------------------------------------------------------------

This project will effectively minimizes the number of transactions needed to settle debts among the banks
