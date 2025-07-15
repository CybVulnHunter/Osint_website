# OSINT Webcam and CCTV Recon

This project is for educational purposes only. It helps security researchers, students, and ethical hackers find open webcams and CCTV cameras using public sources.

> **Disclaimer:** Do not try to hack or access private cameras. This information is only for public, open devices and for ethical learning.

---

## 🔍 What is in this repo?

This repo includes:
- Websites that show public/open cameras
- OSINT search engines for devices like webcams, routers, etc.
- Google search tricks (called “Google Dorks”) to find cameras
- Resources for learning passive OSINT camera reconnaissance

---

## 🌐 Websites to View Public Cameras

### United Kingdom

| Website | Description |
|---------|-------------|
| [insecam.com](http://insecam.com) | Open UK-based webcams |
| [opentopia.com](http://opentopia.com) | Open webcams in UK and globally |
| [earthcam.com](http://earthcam.com) | Map of public webcams |
| [worldcam.eu](http://worldcam.eu) | European open webcams |
| [ukweathercams.co.uk](https://ukweathercams.co.uk) | Weather station CCTV in the UK |
| [see.cam](https://see.cam) | UK open camera feeds |
| [skylinewebcams.com](https://www.skylinewebcams.com) | Live UK webcams |
| [motorwaycameras.co.uk](https://www.motorwaycameras.co.uk) | Motorway traffic cameras |
| [trafficcameras.uk](https://trafficcameras.uk) | CCTV from UK roads and highways |
| [tfljamcams.net](https://tfljamcams.net) | London transport CCTV with 3-month archive |

---

### 🌍 Global (International)

| Website | Description |
|---------|-------------|
| [nsspot.net](https://nsspot.net) | World map of CCTV & webcams |
| [pictimo.com](https://pictimo.com) | Open global CCTV links |
| [windy.com](https://windy.com) | Weather and webcam locations |
| [see.cam](https://see.cam) | Open CCTV by country |
| [insecam.org](http://insecam.org) | Global CCTV search tool |
| [wxyzwebcams.com](http://wxyzwebcams.com) | Open webcams worldwide |
| [skylinewebcams.com](https://www.skylinewebcams.com) | Open webcams across the globe |
| [webcamtaxi.com](https://www.webcamtaxi.com) | Public webcam streaming links |

---

## 🔍 Google Dorks for Finding Open Cameras

Paste the following search queries into Google to try discovering open webcams (use ethically):

### Axis Network Cameras 

```google
intitle:"Live View / AXIS"
inurl:axis-cgi/mjpg/video.cgi
intitle:"live view" intitle:axis
inurl:axis-cgi/jpg
inurl:indexFrame.shtml "Axis Video Server"


intitle:"NetCamSC*"
intitle:"NetCamXL*"
intitle:"webcamXP 5"
"my webcamxp server!"
intitle:"EVOCam" inurl:"webcam.html"


allintitle:Network Camera NetworkCamera
inurl:/ViewerFrame? intitle:"Network Camera NetworkCamera"
inurl:"view.shtml" "camera"
inurl:"view.shtml" "Network"
inurl:/view.shtml
inurl:/view/index.shtml


inurl:"/cgi-bin/guestimage.html" "Menu"
inurl:1051/viewer/live/index.html
inurl:"/viewer/live/index.html"
inurl:/live.htm intext:"M-JPEG"|"System Log"|"Camera-1"|"View Control"
inurl:"webcam.html"
inurl:"webcam.html" intitle:"InsertPlaceNameHere"
inurl:"MultiCameraFrame?Mode=Motion"
camera linksys inurl:main.cgi
"Camera Live Image" inurl:"guestimage.html"
---


## ⚠️ Important Ethical Note

- Only explore what is **publicly open and accessible**.
- Never exploit, crack, or bypass login pages or protected systems.
- This is for **education, OSINT practice**, and cybersecurity awareness only.

---

## 🤝 Want to Help?

You can contribute by:
- Sharing more camera websites
- Suggesting new Google Dork queries
- Fixing broken links
- Making the list better

Pull Requests are welcome!

---


