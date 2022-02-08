# Setup Paychecks

 This command allows `Killfeed Admin` to configure and setup **Paychecks** within their server's economy system for members belonging to roles. The paychecks may then be [collected](./collect.md) each day to receive any configured paychecks for each role they belong to that has been setup to receive one.

> #### Command invoke: ```!paycheck``` Command Aliases: ```!pc```
> + Subcommands: Refer below to **Usage**


!!! note
> + Multiple paychecks may be configured for whichever roles you want to be able to receive one. If a member belongs to 3 roles, and those roles are configured to receive a paycheck, then the member will receive all 3 paychecks upon collection.
> + This command __must__ be executed witihin the dedicated channel for **Economy** commands or it will result in an error message; reference [Dashboard](../dashboard/dashboard.md) to configure the module dedicated channels.
> 
> ![screenshot](../img/bal_error.png)

!!! usage
```
!(paycheck | pc) (create | add)  <@Role> <Amount> <On | Off (off = money gets added to cash)>
!(paycheck | pc) (remove | delete) <Paycheck ID>
!(paycheck | pc) list
```

!!! example

``` {.sql title="Paycheck Command Examples" linenums="1"}
!paycheck add @Survivor 1999 on
!pc add @RoleOne 2500 on
!paycheck create @RoleTwo 2500 off
!pc create @RoleThree 2500 on
!pc delete 12
!pc remove 12
!paycheck list
!pc list
```
> ![screenshot](../img/paycheck.png)