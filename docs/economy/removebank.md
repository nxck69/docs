# Remove Money from Bank
 This command allows `Killfeed Admin` to easily remove amounts of currency from a member's bank account.

> #### Command invoke: ```!removebank``` Command Aliases: ```!removeBank | !remove-bank```

!!! note
> + The command will not work if executed with an argument to ping a role, only individual members.
> + `Killfeed Admin` always retain ability to perform commands to adjust a member's balance amounts despite being banked or on-hand.

!!! usage
```
!removebank <amount> <@Member>
```

!!! example

``` {.sql title="Remove Bank Command Examples" linenums="1"}
!removebank 10000 @nxck69_
!remove-bank 20000 @nxck69_
!removeBank 1500 @nxck69_
```