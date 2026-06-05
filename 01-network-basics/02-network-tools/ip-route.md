# ip route

Shows the routing table.

## Example

ip route

## My Output

default via 192.168.80.1 dev eth0

192.168.80.0/20 dev eth0 proto kernel scope link src 192.168.94.127

## Meaning

default = default route

192.168.80.1 = gateway

eth0 = network interface

192.168.94.127 = my local IP address

## Why use it?

- Check default gateway
- Troubleshoot routing problems
- See where traffic is sent
