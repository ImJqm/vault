#school/s2026/cs3 

Finally got the base IMS api working (i think)

Okay all inv methods working

```
james@m4-mac-mini-wifi ims-gui % javac -cp "lib/gson-2.10.1.jar" src/*.java && \
java  -cp "src:lib/gson-2.10.1.jar" Main

Note: src/Inventory.java uses or overrides a deprecated API.
Note: Recompile with -Xlint:deprecation for details.
Updated quantity of product with pid 01
╭──────────────┬───────┬─────────┬──────────╮
│ Name         │ Pid   │ Price   │ Quantity │
├──────────────┼───────┼─────────┼──────────┤
│Product 1     │01     │$10.99   │55        │
╰──────────────┴───────┴─────────┴──────────╯
ID: 01 Name: Product 1 55x$10.99
Created product with Product ID: 02
╭──────────────┬───────┬─────────┬──────────╮
│ Name         │ Pid   │ Price   │ Quantity │
├──────────────┼───────┼─────────┼──────────┤
│Product 1     │01     │$10.99   │55        │
├──────────────┼───────┼─────────┼──────────┤
│Cool Prod     │02     │$1.88    │2         │
╰──────────────┴───────┴─────────┴──────────╯
Removed product with product ID "02"
Updated quantity of item with Product ID: 01 to 2
╭──────────────┬───────┬─────────┬──────────╮
│ Name         │ Pid   │ Price   │ Quantity │
├──────────────┼───────┼─────────┼──────────┤
│Product 1     │01     │$10.99   │2         │
╰──────────────┴───────┴─────────┴──────────╯
```

Now We need to craft a gui, Im thinking tokyo night theme