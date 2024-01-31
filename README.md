# Networking

# Overview
This document provides an overview of Ubiquiti, a network solution that is cost-effective and offers software options and power to meet specific requirements. It emphasizes the expandability of the system, allowing for upgrades without replacing the router or redoing network settings. The document also includes terminology definitions such as router, gateway, access point, switch, and VLAN. It then lists the hardware components recommended.
## Why Ubiquiti?

Ubiquiti is the best network solution for our needs at a reasonable price. Most network solutions that you can find at the local Best Buy or on Amazon do not have the software options or power to handle what we require. This system also offers excellent expandability. For example, if we need more range, we can upgrade our Access Point (AP) without replacing the router or redoing all our network settings.

## Terminology

- Router: A networking device that connects different networks and forwards data packets between them. Routers operate at the network layer (Layer 3) of the OSI model and use IP addresses to make forwarding decisions.
- Gateway: A device or software component that connects different networks and facilitates communication between them. It serves as an entry and exit point for data traffic between networks, often translating between different networking protocols.
- Access Point: A device that allows Wi-Fi-enabled devices to connect to a wired network using Wi-Fi. Access points are commonly used in wireless networks to provide connectivity and access to the network infrastructure.
- Switch: A networking device that operates at the data link layer (Layer 2) of the OSI model and is used to connect devices within the same local area network (LAN). Unlike hubs, switches forward data only to the specific device it is intended for, improving network efficiency.
- VLAN (Virtual Local Area Network): A logical segmentation of a network into distinct broadcast domains. VLANs are created to enhance network performance, security, and management by grouping devices together based on factors such as function, department, or project, regardless of their physical location.

## Hardware

- Router and Gateway: [Ubiquiti UDM Pro](https://store.ui.com/us/en/pro/category/all-unifi-cloud-gateways/products/udm-pro)
- Access Point: [Ubiquiti U6 Lite](https://store.ui.com/us/en/pro/category/all-wifi/products/u6-lite)

## Networks

- BV Band Electronics:
The main WiFi network that staff/students use. Based on their RADIUS login permissions, their devices will be automatically granted the correct permission level and device access.
- BV Band IoT:
This network is designed for our low-power IoT devices, such as smart energy plugs for our power management system. This network operates on the 2.4GHz frequency only and has lower priority than our other networks. It is not used by students or staff.
- BV Band Lighting:
Similar to our IoT network, this network is designed for our Lighting Nodes. It is optimized for high throughput and signal distance.
- BV Band Guest:
This network is rarely used but is quite useful when needed. It is used if any staff/student or visitor needs temporary access to components of the cart. Sign-on is handled by expiring codes that will only work one time. Codes are infrequently generated.

## Extras

- Our cart has the ability to connect to any WiFi network available and pass that connection to any WiFi or ethernet connected device. This is extremely useful for updating our hardware and remote accessing our Mac Mini via TeamViewer for remote diagnostics or Mainstage/Ableton rig setup. The Mac Mini also has local remote access for multiple students/staff who needs to view the display on the cart. This solution will unfortunately not work for remoting into the Mac due to our districts networking policies (TeamViewer is allowed for us). Parsec is used for local remote access.
- The UDM Pro is expensive, we were planning on purchasing the [UniFi Express](https://store.ui.com/us/en/pro/category/all-unifi-cloud-gateways/products/ux) or the [Dream Router](https://store.ui.com/us/en/pro/category/all-unifi-cloud-gateways/products/udr) initially. Those are very good options, but have their drawbacks.

## Authors
- [@_rileyspence](https://github.com/rileyspence)

Some Parts of this doccuemnt are writen by AI


Last Updated 1/31/2024
