# Network Troubleshooting

## Troubleshooting Framework

### Step 1 - Check IP Address

Command:

ip a

Question:
Do I have an IP address?

---

### Step 2 - Test Loopback

Command:

ping -c 3 127.0.0.1

Question:
Can I reach myself?

---

### Step 3 - Test Gateway

Command:

ip route

Find gateway and test:

ping -c 3 <gateway-ip>

Question:
Can I reach my router?

---

### Step 4 - Test Internet Connectivity

Command:

ping -c 3 8.8.8.8

Question:
Can I reach the internet?

---

### Step 5 - Test DNS

Command:

nslookup google.com

Question:
Can DNS resolve names?

---

## Troubleshooting Flow

IP
→ Loopback
→ Gatewa
→ Internet
→ DNS

---

