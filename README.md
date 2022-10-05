# Subnet Masks

# What is a Subnet?
- Essentially, it is a network inside a network.
- For large companies that want to separate networks by department, they will use subnetting.

# What is the default gateway?
- It just means router.


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
- Routers use subnet masks to route data packets to the right place.
- Ex: Bob answers Alice's letter, but he sends reply to Alice's job rather than her home. Alice's office is quite large with many differents groups. To ensure employees receive their correspondence quickly, the admin team at Alice's workplace sorts mail by department rather than individual employee. 
- After receiving Bob's letter, they look up Alice's department and see she works in Customer Support.
- They send the letter to the Customer Support department instead of to Alice, and the customer support department gives it to Alice
- Alice is the IP address. Customer Support is like a subnet mask.
- By matching Alice to her department, Bob's letter was quickly soirted into the right group of potential recipients. 
- Without the step, office admins have to spend a long time looking for the exact location of Alice's desk.


# How would we subnet?
- It is done by changing the default subnet mask by borrowing some of the bits from the host portion.

<p align="center">
  
<img src="https://user-images.githubusercontent.com/104326475/193961246-5b8093e1-3e14-4cb2-ad55-fe955276b0c6.png" height="100%" width="100%" alt="UAR"/>
  
<p/>
