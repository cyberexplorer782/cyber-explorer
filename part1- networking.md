#  Part 1: Network and Web Fundamentals

##   How Data Travels

###  IP Address (The Digital Mailbox)

* *What it does:* Identifies a device on the internet so data knows where to go.
  
* *Dynamic:* It changes depending on the network you're connected to.
  
* *IPv4:* 32 bits (4 numbers). We officially ran out of them globally.
  
* *The NAT Trick:* Networks use Network Address Translation to let a whole house share just *one* public IP.
  
* *IPv6:* 128 bits (hexadecimal). The future fix for the IPv4 shortage, but adoption is slow because upgrading global hardware is crazy expensive.

###  MAC Address (The Hardware Tattoo)

* *What it does:* Your device's permanent physical footprint. It never changes.
  
* *Local delivery:* While the IP gets data to your router, the MAC address tells the router exactly which physical device in the room gets the packet.

###  From "Hello" to Pixels (The Flow)
1. *Text:* You type "Hello".
2. *Numbers:* Character codes convert it into ASCII numbers (`72, 101, 108, 108, 111`).
3. *Bits:* Numbers turn into binary (`0`s and `1`s).
4. *Physics:* Bits travel as electrical signals or light pulses through fiber optic cables.
5. *Arrival:* Your home router reads the public packet, checks its NAT table, matches it to your private IP, and drops it right at your hardware's MAC address.
