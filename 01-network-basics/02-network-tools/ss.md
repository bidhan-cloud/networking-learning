# What is ss?

ss shows network sockets and listening ports.

## Example

ss -tuln

Meaning:
-t = TCP
-u = UDP
-l = Listening ports
-n = Show numbers, don't resolve names

## Why use it?

Used to check:
- Open ports
- Running network services
- Whether SSH is listening

## Example output

0.0.0.0:22

Means SSH is listening on port 22.
