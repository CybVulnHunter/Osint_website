# Search and Mapping Sites for Cybersecurity and Reconnaissance

---

## 1. shodan.io – Search Engine for Internet-Connected Devices

### Introduction
Shodan is a powerful search engine that indexes data from Internet-connected devices and services. It scans IP addresses across the internet and collects banners, metadata, and service information from open ports.

### Need
Shodan is essential for cybersecurity professionals to discover exposed services, misconfigured devices, and vulnerabilities in real-world systems. It provides intelligence on servers, webcams, routers, IoT devices, and more.

### Usage
- Search for exposed databases, web servers, cameras, and ICS/SCADA systems.
- Use filters like `port`, `org`, `country`, `city`, or `product` to narrow down results.
- Integrate with vulnerability databases to find CVEs associated with devices.
- Utilize the Shodan Quick Start Reference (by Michael Holcomb) for effective query examples.
- Useful for penetration testers, red teamers, and defenders to assess attack surface.


<img width="1541" height="782" alt="image" src="https://github.com/user-attachments/assets/ebcdb020-584a-444b-9528-f8b5d4fae8eb" />


---

## 2. hunter.how – Alternative Search Engine for Internet-Connected Devices

### Introduction
Hunter.how is an open-source alternative to Shodan, focused on indexing and querying internet-facing services and devices.

### Need
Provides additional or backup visibility when Shodan results are limited. It is especially useful in privacy-focused environments or for validating findings from other tools.

### Usage
- Search for devices exposed over the internet.
- View metadata similar to Shodan but with different indexing mechanisms.
- Free and accessible to those conducting OSINT and device discovery.

  <img width="1530" height="732" alt="image" src="https://github.com/user-attachments/assets/cf573e67-5508-4ffd-a179-f6ba46b4a33b" />

---

## 3. zoomeye.org – Search Engine for Internet Devices and Services

### Introduction
ZoomEye is a Chinese-developed cybersecurity search engine, similar to Shodan, that indexes devices, services, and vulnerabilities across the global internet.

### Need
Offers a different geographic and scan perspective, often uncovering data not indexed by Shodan. Valuable for researchers conducting global reconnaissance or investigating threats in Asia-Pacific regions.

### Usage
- Search for exposed devices based on IP, service, or vulnerability.
- Supports advanced filters and data visualization.
- Widely used in malware hunting and infrastructure mapping.

<img width="1545" height="781" alt="image" src="https://github.com/user-attachments/assets/4466deca-cfd8-4e02-86ad-61d247385cde" />


---

## 4. wigle.net – Wi-Fi Mapping and Geolocation Search

### Introduction
WiGLE (Wireless Geographic Logging Engine) collects and maps Wi-Fi networks across the globe, showing SSID, encryption type, signal strength, and geolocation data.

### Need
Useful for wireless reconnaissance, wardriving, and physical location tracking. Helps identify the presence and characteristics of wireless networks in a given area.

### Usage
- Search for Wi-Fi hotspots on a global map.
- Filter results based on SSID, location, or encryption type.
- Requires free account registration to access full details.
- Used in both legal investigations and wireless security assessments.


<img width="1525" height="725" alt="image" src="https://github.com/user-attachments/assets/aacb9b9d-be09-4089-a7d0-e4e0bc4d4ee0" />

---

## 5. wifispc.com – Wi-Fi Location Search Site

### Introduction
WiFiSPC is a web-based service that maps public Wi-Fi networks and helps users locate nearby access points with network details.

### Need
Aids in mapping wireless infrastructure during site surveys or red teaming exercises. Also helpful for planning physical reconnaissance or evasion paths in urban areas.

### Usage
- Visualizes public Wi-Fi spots by city or region.
- Displays basic info like SSID, signal strength, and user ratings.
- Can be used alongside other tools for real-world signal mapping.

<img width="1520" height="730" alt="image" src="https://github.com/user-attachments/assets/9ccf249f-f0d1-4df6-948e-ba89d31b722d" />



---

## 6. ipinfo.io – IP Information and Ownership Lookup

### Introduction
IPinfo is a geolocation and IP metadata lookup service that provides ownership, ASN, location, and organization details for any IP address or block.

### Need
Used to attribute IP addresses to organizations, identify hosting providers, or filter traffic based on region or provider. It plays a critical role in threat hunting, fraud detection, and incident response.

### Usage
- Enter any IP to get ISP, location, organization, ASN, and domain.
- Use the bulk IP API for large-scale enrichment of logs.
- Helps analysts track traffic back to source or identify suspicious infrastructure.

<img width="1525" height="726" alt="image" src="https://github.com/user-attachments/assets/c1257a12-13f1-4b6b-8ac9-6336a94de609" />


---

## Summary Table

| Site             | Type                           | Best For                                              |
|------------------|--------------------------------|--------------------------------------------------------|
| **shodan.io**     | Device search engine           | Internet-exposed device discovery and vulnerability search |
| **hunter.how**    | Device discovery               | Alternative to Shodan for device exposure analysis     |
| **zoomeye.org**   | Global device search           | Asia-focused scanning and vulnerability data           |
| **wigle.net**     | Wi-Fi mapping                  | Locating and analyzing wireless access points          |
| **wifispc.com**   | Wi-Fi hotspot map              | Finding nearby Wi-Fi details with mapped visuals       |
| **ipinfo.io**     | IP metadata lookup             | IP ownership, geolocation, and ASN investigation       |

---
