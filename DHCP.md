DHCP (Dynamic Host Configuration Protocol)

**What is DHCP?

Have you ever connected your phone to a new Wi-Fi network and noticed that it starts working immediately without asking you to enter an IP address? That's because of DHCP (Dynamic Host Configuration Protocol).

DHCP is a networking protocol that automatically gives a device everything it needs to communicate on a network, including an IP address. Instead of configuring network settings manually for every device, DHCP does it in just a few seconds.

You can think of DHCP as a helper that welcomes every new device to the network and makes sure it gets the correct network information.



Why Do We Need DHCP?

Imagine a classroom where every student has to choose their own roll number. Some students might pick the same number, while others might forget to choose one at all. It would quickly become confusing.

DHCP solves this problem by automatically assigning a unique IP address to every device, ensuring there are no conflicts and making network management much easier.

---

How Does DHCP Work?

DHCP follows a simple four-step process known as DORA.

1. Discover

When a device connects to a network, it asks:

"Is there a DHCP server that can help me?"

2. Offer

The DHCP server replies:

"Yes! I have an IP address available for you."

3. Request

The device responds:

"I'd like to use that IP address."

4. Acknowledge

Finally, the server confirms:

"Done! The IP address is now yours."

After these four steps, the device is ready to communicate with other devices and access the internet.

---

A Real-Life Example

Think about checking into a hotel.

- You arrive and ask if a room is available.
- The receptionist offers you a room.
- You accept the room.
- The receptionist hands you the key.

Just as the receptionist assigns you a room, the DHCP server assigns an IP address to your device.

---

What Information Does DHCP Provide?

DHCP doesn't just assign an IP address. It also provides important network details such as:

- IP Address
- Subnet Mask
- Default Gateway
- DNS Server
- Lease Time (how long the device can use the assigned IP address)

---

Why Is DHCP Useful?

DHCP makes networking faster, easier, and more reliable.

Its main benefits include:

- Automatically assigning IP addresses.
- Reducing manual work for network administrators.
- Preventing duplicate IP addresses.
- Saving time when new devices join the network.
- Making it easy to manage both small and large networks.

---

Security Risks

Although DHCP is very useful, attackers can also misuse it.

A Rogue DHCP Server is a fake server that provides incorrect network settings, which can redirect users' traffic.

A DHCP Starvation Attack happens when an attacker requests a large number of IP addresses until the DHCP server has none left to assign to legitimate users.

---

How Can We Protect DHCP?

Some common security measures include:

- Enabling DHCP Snooping on network switches.
- Allowing only trusted DHCP servers.
- Monitoring the network for unusual activity.
- Using proper network security policies.

---

Conclusion

DHCP is one of the most important protocols in computer networking. It quietly works in the background every time a device joins a network, automatically providing the information needed to communicate. Without DHCP, setting up networks would be much more time-consuming and prone to errors. Understanding DHCP is essential for anyone interested in networking, cybersecurity, or system administration.