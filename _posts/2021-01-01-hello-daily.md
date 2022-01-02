---
title: 'Hello Daily'
date: 2021-01-01
permalink: /daily/hello-daily/
tags:
---

Kicking off the daily StarkNet series with boilerplate!

The Contract
======
```
%lang starknet
%builtins pedersen range_check

from starkware.cairo.common.cairo_builtins import HashBuiltin

# Returns the current balance.
@view
func get_message{syscall_ptr : felt*, pedersen_ptr : HashBuiltin*, range_check_ptr}() -> (
        res : felt):
    let message = 'Hello Daily'
    return (message)
end
```
mainnet address: 0x014a10844d94cbfaedf7b9ea802fbff1cfce9c75d90715e16b9c342ff2d5e8c8
[code](https://github.com/0xNonCents/Hello-Daily-01-01-2021)


Demo
------
Coming Soon