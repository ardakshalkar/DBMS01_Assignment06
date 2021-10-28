**P01.A** Insert new user with your name and surname 
**P01.B** Insert many new users with name of your friends  
**P01.C** Delete from `SuspiciousTransactions` all messages from account number 8  
**P01.D** Change name of user number 7 to name 'Mike'  
**P01.E** Update `Users` table if name ends with `a` make its gender M  

**Instead or together with assignments above practice instructor can give extra assignments**

---
**P02.A** Copy transactions *(do not confuse with Transactions operator)* which were performed at April from table `Transactions` to table `SuspiciousTransactions`   

**P02.B** Delete last 3 transactions

**P02.C** Update all Accounts which belongs to Users *(all account tables which has user_id not null)* make money less on 10 $  

**P02.D** You have received new file with Company names, you shoud add them to `Companies` table.  
Note: Each company should have unique name (so, no two companies can have same name). If it is already exist in table, update it
| Title  | Country |
|:--|:--|
| Google | USA     |
| Jayo   | Russia  |
| Yandex | Russia  |
| Roombo | Poland  |

---

Transactions  
**P03.A** Create transaction   
that subtracts 102$ from account 1  
then adds 100$ to account 2  
and stores 2$ to account 9999  
and add information about this operation to table `Transactions`

**P03.B** 
Use transactions  
Update accounts, if account's money is less than 0, update as x*1.07, if more than 0 it should convert to x * 1.2

**P03.C** Use transactions  
Copy all transactions that were sent to account of companies which are from Russia into `SuspicousTransactions`   
Delete all transactions that are sent to account which are located in Russia
