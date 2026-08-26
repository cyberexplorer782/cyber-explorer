Part 1: Network and Web Fundamentals.
## Goal: To understand how data travels across the internet.
 
   - Network Fundamentals 

- IP address: 

An IP address is what identifies my computer.
It is not permanent, yet it plays a crucial role
in data transmission, consisting of 4 numbers that 
represent a total of 32 bits.
  
 IPv4: 
  
 What i know about this address is that they are
 scattered all over the world and have run out.. 
      
 yet many still prefer to use them because of their 
 simplicity and because upgrading the entire global
 infrastructure to IPv6 is incredibly  expensive  and  
 takes a long time that we don't really have.  
      
  To keep IPv4 alive , networks use a trick called NAT 
  (network Address Translation), which lets multiple devices 
  share just one public IP.
  
- Ipv6:
  
  This is the alternative to IPv4 addresses.
  
  While they offer a solution  to the exhaustion of IPv4 addresses,
  there are some downsides.

  There is a reason  people haven't fully embraced them yet.
  The addresses are  extremely long and complex.

  Furthermore, networks running exclusively  on IPv4
  cannot communicate directly with those using only IPv6.
  
  Finally, transitioning to IPv6 requires  upgrading millions
  of old routers globally, which costs billions of dollars.

- MAC address:

  This is a special address, acting as
  your unique digital footprint
  that cannot be permanently changed .
  
  While your IP address is
  responsible for delivering the data across the internet to your router,
  the MAC address represents your specific device's location inside the local network.
  
  This is how the router knows exactly were to send the data.

  Now that you understand the role of these basic but most important concepts,
  i will explain how your router works.
  
  Imagine that your router is the boss of your house,
  it gets one public IP address  from the internet provider
  and chooses what the private IP address of your phone will be. 

  For example , when your friend send you a text message like 
  " Hello, his message is instantly transformed into data packets 

  made of numbers (the letters " H-e-l-l-o" become ASCII numbers : 72, 101,108,108,111).
  These numbers are are then converted in to binary bits( 0s and 1s).

The bits represent the actual  light pulses or electrical signals that through the fiber 
optic cables   and reach your home  router at lightening speed. 

Therefore, using the NAT table, your router translates the public packet and sends it  directly to your private IP address, delivering it to the final hardware location: your unique MAC address.

  

