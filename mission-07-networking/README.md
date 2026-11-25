# Mission 7 — How computers communicate

> Draft based on the assignment. Replace observation and reflection prompts with your own verified work and rewrite explanations in your own words before submission. Do not claim GitHub actions until they are actually visible.

## 1. Task / objective
Complete the tasks listed in this mission of the Digital Detective assignment.

## 2. Work completed and answer notes

## 7.1 Network concepts

| Concept | Explanation | Example |
|---|---|---|
| LAN | A local network covering a limited area. | Home Wi-Fi or an office network. |
| MAN | A network spanning a city or large campus. | A city-wide municipal network. |
| WAN | A network connecting large geographic areas. | The Internet. |
| DNS | A naming system that looks up network addresses for domain names. | Looking up the address for `example.com`. |
| Router | Forwards data between networks and chooses a route for packets. | A home router connecting devices to an ISP. |
| Protocol | Agreed rules and message formats devices use to communicate. | HTTPS for secure web communication. |
| Packet switching | Sends data in packets that can travel across networks and be reassembled. | Web page data sent across the Internet. |
| Client-server | A client requests a service or resource; a server provides it. | A browser requests a page from a web server. |

## 7.2 Connectivity and DNS (personal observation required)

A connectivity test such as `ping example.com` checks whether a host responds over the network and gives timing/loss information; some hosts or networks block ping, so no reply alone does not prove the website is unavailable. A DNS lookup (for example, `nslookup example.com`) asks DNS for records such as IP addresses associated with a domain. DNS lets a browser find the network destination for a human-readable name.

**Your actual observation:** [Record the command/tool used and a brief privacy-safe result. Do not include your own IP, Wi-Fi name, device name, or identifying output.]

## 7.3 What happens when you open a website

1. You enter a URL in the browser; it identifies the domain and requested page.
2. The browser asks DNS for an address associated with the domain.
3. The computer sends packets through its local network and router toward that server.
4. The browser and server establish a connection and agree on the application protocol; HTTPS also sets up encrypted TLS communication.
5. The browser sends an HTTP request for the page or resource.
6. The server processes the request and returns a response, often containing HTML, styles, scripts, or data.
7. The browser renders the response and displays the page; additional resources may require more requests.

---

## 3. Commands / tools used
[Add the commands and applications you personally used, and explain their purpose.]

## 4. My understanding
[Rewrite the notes above in your own words and include what you observed.]

## 5. Difficulties faced
[Record actual difficulties, or “No major difficulties.”]

## 6. How I resolved them
[Record actual resolutions, or “Not applicable.”]

## 7. Evidence / files
[Add files and privacy-safe evidence actually included.]

## 8. Commit details
[Add the actual commit message and confirm that it was pushed.]

### Privacy-safe lookup actually performed

A one-packet connectivity check to `example.com` received one reply with 0% packet loss (about 146.5 ms round trip in this run). `nslookup example.com` returned public addresses `104.20.23.154` and `172.66.147.243`. Results can differ by network and time. No local IP address or Wi-Fi details are included.
