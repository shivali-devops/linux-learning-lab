# Networking Fundamentals

# Overview 
- IP 
- CIDR
- Subnet
- Port

---
# What is IP Address?

An IP Address (Internet Protocol Address) is a unique numerical label assigned to each device connected to a computer network that uses the Internet Protocol for communication. It serves two main purposes:

It uniquely identifies a device (computer, phone, server, etc.) so they can communicate with each other.

Think of it like:

- House address → to receive letters.
- IP address → to send/receive data packets.

Examples:
- IPv4: 192.168.1.1
- IPv6: 2001:db8::1

# Types of IP Address Configuration

When a device joins a network (like Wi-Fi), it needs an IP. There are two ways to assign it:

# 1. Manual (Static Configuration)
- The user (or admin) manually sets the IP address in device settings.
- It doesn’t change unless you change it yourself.
- Used for servers, printers, routers where address must be constant.

# 2. DHCP (Dynamic Host Configuration Protocol)
- A server (DHCP server, usually your router) automatically assigns an IP to devices.
- IP can change each time you reconnect.
- Example: When you connect to Wi-Fi, you don’t manually type an IP → your router (via DHCP) gives you one.

# IPv4 (Internet Protocol version 4)
- Address size: 32-bit
- Format: Decimal, written as four numbers separated by dots. Example: 192.168.0.1
- Header size: 20 bytes
- Configuration: Can be manual or DHCP (Dynamic Host Config Protocol).
- Broadcast - supported (In broadcast, a message is sent from one device to all devices in the same network segment.)

# IPv6 (Internet Protocol version 6)
- Address size: 128-bit
- Format: Hexadecimal, written as 8 groups separated by colons. Example:2001:0db8:85a3:0000:0000:8a2e:0370:7334
- Header size: 40 bytes
- Configuration: Autoconfiguration possible (Autoconfig + DHCPv6).
- Broadcast - Not supported (Multicast supported - In multicast, data is sent from one source to multiple selected receivers that are part of a multicast group.)