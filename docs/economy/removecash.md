# Remove Money from Cash
 This command allows `Killfeed Admin` to easily remove amounts of currency from a member's cash on-hand amount.

> #### Command invoke: ```!removecash```

!!! note
> + The command will not work if executed with an argument to ping a role, only individual members.
> + `Killfeed Admin` always retain ability to perform commands to adjust a member's balance amounts despite being banked or on-hand.

!!! usage
```
!removecash <amount> <@Member>
```

!!! example

``` {.sql title="Remove Cash Command Examples" linenums="1"}
!removecash 10000 @nxck69_
!remove-cash 20000 @nxck69_
!removeCash 1500 @nxck69_
```