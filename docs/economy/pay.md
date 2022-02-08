# Paying Others

 This command allows all users to pay another member from the server with their cash-on-hand amount. 

> #### Command invoke: ```!pay```   | Command  alias: ```!transfer | !giveMoney | !give-money``` 

!!! note 
> + This command __must__ be executed witihin the dedicated channel for **Economy** commands or it will result in an error message; reference [Dashboard](../dashboard/dashboard.md) to configure the module dedicated channels.
> 
> ![screenshot](../img/bal_error.png)

!!! usage
```
!pay <amount> <@Member>
```

!!! example

``` {.sql title="Pay Command Examples" linenums="1"}
!pay <amount> <@Member>
!transfer <amount> <@Member>
!giveMoney <amount> <@Member>
!give-money <amount> <@Member>
```