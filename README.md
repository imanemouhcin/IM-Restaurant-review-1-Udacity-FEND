# IM-Restaurant-review-1-Udacity-FEND

## Live Version
https://imanemouhcin.github.io/IM-Restaurant-review-1-Udacity-FEND/


## Project Overview

For the Restaurant Reviews projects, you will convert a static webpage to a mobile-ready web application. 
The design is responsive on different sized displays and accessible for screen reader use. You will also use a service worker to an offline experience for users.
Responsive design, accessibility and offline use.


* Main page:
  - A Map showing the restaurants addresses
  - Filter the restaurants according to: "Neighborhood", and "Cuisine".
  - Restaurant cards - showing photo, name, neighborhood, address, view details button

* Individual restaurant :
  - Details (photo, name, neighborhood, address)
  - The restaurant map
  - Opening hours
  - Reviews for the restaurant

##  Features

### Responsive Design:
  - Making UI compatible with a range of display sizes 
  - Responsive images ( appropriate to the viewport)

### Accessiblity:
  - Accessible images with alternate text
  - Semnatically defined elements and ARIA roles

### Offline Availability:
 Use Service worker: the app is available offline after the first use.


## To run Localy 

  1. After download, use a simple HTTP server to serve up the site files on your local computer.
  - If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.
  - Navigate to project folder in your terminal.
  - Check the version of Python you have: `python -V`.
  - If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.)
  - For Python 3.x, you can use `python3 -m http.server 8000`

  2. With your server running, visit the site: `http://localhost:8000`.
  
## REFERENCES

* Adding a Service Worker and Offline into your Web App (https://developers.google.com/web/fundamentals/codelabs/offline/)
* Lab: Responsive Images (https://developers.google.com/web/ilt/pwa/lab-responsive-images)
