IPv4 has reserved the 224.0.0.0 to 239.255.255.255 addresses as a multicast range.

| Network Address and Prefix | RFC 1918 Private Address Range |
| -------------------------- | ------------------------------ |
| 10.0.0.0/8                 | 10.0.0.0 - 10.255.255.255      |
| 172.16.0.0/12              | 172.16.0.0 - 172.31.255.255    |
| 192.168.0.0/16             | 192.168.0.0 - 192.168.255.255  |
Loopback addresses (127.0.0.0 /8 or 127.0.0.1 to 127.255.255.254)

Link-local addresses (169.254.0.0 /16 or 169.254.0.1 to 169.254.255.254)

- **Class A (0.0.0.0/8 - 127.0.0.0/8) -** Designed to support extremely large networks with more than 16 million hast addresses. Class A used a fixed /8 prefix with the first octet to indicate the network address and the remaining three octets for host addresses (more than 16 million host addresses per network).
- **Class B (128.0.0.0/16 - 191.255.0.0/16) -** Designed to support the needs of moderate to large size networks with up to approximately 65,000 host addresses. Class B used a fixed /16 prefix with the two high-order octets to indicate the network address and the remaining two octets for host addressing (more than 65,000 host addresses per network).
- **Class C (192.0.0.0/24 - 223.255.255.0/24) -** Designed to support small networks with a maximum of 254 hosts. Class C used a fixed /24 prefix with the first three octets to indicate the network and the remaining octet for the host addresses (only 254 host addresses per network).
**Note:** There is also a Class D multicast block consisting of 224.0.0.0 to 239.0.0.0 and a Class E experimental address block consisting of 240.0.0.0 - 255.0.0.0.

 `Because it's too hard to remember so I have to make a note`

