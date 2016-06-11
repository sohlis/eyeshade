## Eyeshade
### _Knowing feels so good_

You input your bank stuff:
```
prompt: bank:  (wells)
prompt: transactions:  (50)
prompt: username:  (plaid_test)
prompt: password:  (<default hidden>)
```
You get:
```
» 200 | ATM Withdrawal | 2014-07-21
» 240 | Online Transfer from External Sav ...3092 | 2014-07-24
» 2307.15 | Apple Store | 2014-06-23
» 3.19 | Gregorys Coffee | 2014-06-21
» 80 | ATM Withdrawal | 2014-06-08
» -240 | Online Transfer from Chk ...1702 | 2014-06-02
» 240 | Online Transfer to Sav ...9606 | 2014-06-01
» -0.93 | Interest Payment | 2014-05-17
» 12.74 | Golden Crepes | 2014-05-12
» 7.23 | Krankies Coffee | 2014-05-09
» 118.23 | Banana Republic | 2014-04-26
» -800 | Venmo Cashout 18375552 | 2014-04-20
» 120 | Venmo Payment 16991172 | 2014-04-19
» 5.32 | Octane Coffee Bar and Lounge | 2014-04-17
» 28.57 | Papa Johns Pizza | 2014-04-11
» -3042.44 | Company Payroll | 2014-03-27
```


#### Run it, fellow traveler
`./index`

##### Your `.env` file looks like
```
PLAIDCLIENTID={plaid client-id}
PLAIDSECRET={plaid secret}
```
