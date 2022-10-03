# Subnetting

# What is a Subnet?
- Essentially, it is a network inside a network.



# Benefits of Subnetting
- Subnets make networks more efficient.
- Through subnetting, a network traffic can travel a shorter distance without passing through unnecessary routers to its destination.
- When a network receives data packets from another network, it will sort and route those packets by subnet so that the packets do not take an inefficient route to their destination.
- Subnetting narrows down the IP address to use within a range of devices.

# What is an IP address?
- Every device that connects to the internet is a unique IP address. 
- It is how the network identifies each devices.

# Identifying parts of an IP address (IPv4 addresses)
- IPv4 is presented in the form of four decimal numbers separated by periods like 203.0.113.112.
- Every IP address has two parts.
- First part indicates which network the address belongs to.
- Second part specifies the device within that network.

# Network classes
- Networks are categorized into different classes.
- Class A network: Everything before the first period indicates the network, and everything after it specifies the device within that network.
- Example: 203.0.113.112
- 203 refers to the network....... and the device by 0.113.112.

# What is a subnet mask?
- Subnet mask is like an IP address, but for only internal usage within a network.
- Routers use subnet masks to route to route data packets to the right place.
