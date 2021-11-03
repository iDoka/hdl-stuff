
add to the begin in every synthesizable verilog file to raising an error if signal type not defined well:

```
`default_nettype none
```

add to the end in every synthesizable verilog file for leave external modules untouchable:

```
`default_nettype wire
```
