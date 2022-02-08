# Withdraw Cash

 This command allows all users to deposit any currency gained through gameplay or use of the bot's other economy commands directly into their bank accounts. If executed by itself it will automatically withdraw the entire amount of currency a member has in their bank. It can also be executed alongside of an amount argument, which will withdraw only the given amount from the bank account, and retain the remainder in savings.

> #### Command invoke: ```!withdraw```     | Command  alias: ```!with```

!!! note
> + The bank account feature allows members to retain their currency safe and secure from being robbed by other members. 
> + `Killfeed Admin` always retain ability to perform commands to adjust a member's balance amounts despite being banked or on-hand.
> + This command __must__ be executed within the dedicated channel for **Economy** commands or it will result in an error message; reference [Dashboard](../dashboard/dashboard.md) to configure the module dedicated channels.
> 
> ![screenshot](../img/bal_error.png)

!!! usage
```
!with [amount]
```

!!! example

``` {.sql title="Withdraw Command Examples" linenums="1"}
!withdraw
!with <amount>
```