# Networking

## IP Addressing

- What does `192.168.0.110/24` ip address means?

This can be broken down into two parts, `192.168.0.110`, which is the current host ip address.
`/24` is used to determine the **subnet mask** of the network.
Here it means, that 24 1's followed by all 0. That is, `11111111`.`11111111`.`11111111`.`00000000`, `255.255.255.000`
This is the subnet marks.

What this subnet marks implies:

- Network address - `192.168.0.0`
- Broadcast address - `192.168.0.255`
- Usable Host address - `192.168.0.1...254`
