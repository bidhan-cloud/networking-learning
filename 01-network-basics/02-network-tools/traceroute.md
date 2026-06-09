# What is traceroute?

Traceroute shows the path packets take from my device to a destination.

## Example

traceroute google.com

If traceroute is not installed:

sudo apt install traceroute

## What is a hop?

A hop is one network device that forwards traffic toward the destination.

Example:

Laptop
↓
Home Router
↓
ISP Router
↓
Internet Router
↓
Google Network
↓
Google Server

Each stop is called a hop.

## My Lab

Command:

traceroute google.com

First hop:

192.168.80.1

This is my gateway/router.

## Why use traceroute?

Used to:

- Find network delays
- Diagnose routing issues
- Identify where connectivity problems occur
- Troubleshoot slow websites

## Key Points

- Traceroute shows the journey to a destination
- Hop = one stop on the path
- First hop is usually the gateway/router
- Multiple hops exist because data travels through many routers
- Network engineers use traceroute to troubleshoot problems

## What I Learned

Data does not travel directly to Google.

My traffic follows multiple hops before reaching the destination.

The first hop is usually my router.
