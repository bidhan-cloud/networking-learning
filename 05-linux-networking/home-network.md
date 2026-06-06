# Build a Home Network From Scratch

## Goal

Understand how a device reaches a website on the internet.

## Network Map

Laptop
↓
WiFi / Ethernet Interface
↓
Router (Gateway)
↓
Internet
↓
Google Server

## My Network Information

Hostname:
vic-15-fa2705np

Private IP:
192.168.94.127

Gateway:
192.168.80.1

Public IP:
87.196.81.101

## Complete Flow

When I open:

google.com

### Step 1

DNS resolves the name:

google.com → Google IP

Command:

nslookup google.com

### Step 2

Routing checks the path.

Command:

ip route

### Step 3

Traffic goes to my gateway.

Gateway:

192.168.80.1

### Step 4

NAT translates:

Private IP → Public IP

### Step 5

TCP connects to:

Port 443 (HTTPS)

### Step 6

Google sends a response.

### Step 7

The browser displays the webpage.

## Commands Used

hostname

ip a

ip route

curl ifconfig.me

nslookup google.com

## Summary

A website request follows this path:

Device
→ Network Interface
→ Gateway Router
→ Internet
→ Google Server
→ Response Back
