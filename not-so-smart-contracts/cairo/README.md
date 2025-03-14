# (Not So) Smart Contracts

This repository contains examples of common Cairo smart contract vulnerabilities, including code from real smart contracts. Use Not So Smart Contracts to learn about Cairo vulnerabilities, as a reference when performing security reviews, and as a benchmark for security and analysis tools.

## Features

Each _Not So Smart Contract_ includes a standard set of information:

* Description of the vulnerability type
* Attack scenarios to exploit the vulnerability
* Recommendations to eliminate or mitigate the vulnerability
* Real-world contracts that exhibit the flaw
* References to third-party resources with more information

## Vulnerabilities

| Not So Smart Contract | Description |
| --- | --- |
| [Improper access controls](access_controls) | Broken access controls due to StarkNet account abstraction |
| [Integer division errors](integer_division) | Unexpected results due to division in a finite field |
| [View state modifications](view_state) | View functions don't prevent state modifications |
| [Arithmetic overflow](arithmetic_overflow) | Arithmetic in Cairo is not safe by default |
| [Signature replays](replay_protection) | Account abstraction requires robust reuse protections |
| [L1 to L2 Address Conversion](l1_to_l2_address_conversion) | L1 to L2 messaging requires L2 address checks |
| [Incorrect Felt Comparison](incorrect_felt_comparison) | Unexpected results can occur during felt comparison | 
| [Namespace Storage Var Collision](namespace_storage_var_collision) | Storage variables are not scoped by namespaces |
| [Dangerous Public Imports in Libraries](dangerous_public_imports_in_libraries) | Nonimported external functions can still be called |

## Credits

These examples are developed and maintained by [Trail of Bits](https://www.trailofbits.com/).

If you have questions, problems, or just want to learn more, then join the #ethereum channel on the [Empire Hacking Slack](https://empireslacking.herokuapp.com/) or [contact us](https://www.trailofbits.com/contact/) directly.
