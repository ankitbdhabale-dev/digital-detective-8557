# Mission 7 — How computers communicate

> AI-assisted answer notes. The connectivity and DNS checks below were run during this session.

## Network concepts

- LAN: network over a small local area, such as a home or office.
- MAN: network across a city or large campus.
- WAN: network across large distances; the Internet is an example.
- DNS: looks up network records for a domain name.
- Router: forwards packets between networks.
- Protocol: agreed rules for communication; HTTPS is used for secure web traffic.
- Packet switching: divides data into packets that can travel across networks and be reassembled.
- Client-server: a client requests a resource and a server responds.

## Actual connectivity and DNS observation

A one-packet ping to example.com received one reply, with 0% packet loss and about 146.5 ms round trip in this run. nslookup example.com returned public addresses 104.20.23.154 and 172.66.147.243. DNS and ping results can vary by time and network. No local IP or Wi-Fi name is included.

## When opening a website

The browser reads the URL, uses DNS to find the domain’s address, connects through the local network and router, sends an HTTP request, and receives a response. HTTPS also uses TLS encryption. The browser processes the response and renders the page; extra resources may require more requests.

## AI-assisted learning note

DNS connects readable domain names to network records. A browser and web server communicate by sending requests and responses in packets.

## Commit and evidence

The Mission 7 README is in mission-07-networking. Original commit: “Explain networking concepts and website communication.”
