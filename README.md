Carpooling-Web-App
===

Carpooling Web App is intended to help the user to share car rides with other users traveling on the same route. The user may intend to share his car or else ride with another user who is willing to share.

The carpooling software is designed and developed in Django framework using GoogleMaps API.

Carpooling Web App is aimed toward a person who is a frequent traveller and is looking for cheap and comfortable mode of transport. It will prove beneficial for office commuters who are headed on a common route and are willing to share the travel cost. Anyone can opt to provide a drive, thus reducing his/her expense. 



:::info
Github Repo: **[Carpooling-Web-App](https://github.com/guptavishakha14/Carpooling-Web-App)**
:::

## Setup
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See getting started for notes on how to deploy the project on a live system.

### Prerequisites
You need to install:
1. [Python 3.6 or above](https://www.python.org/downloads/)
2. [Django 3.0 or above](https://docs.djangoproject.com/en/3.0/intro/install/)
3. [GoogleMaps API](https://developers.google.com/maps/documentation)


---
### Getting Started

Once django is installed, all you need to do is clone this repository.

```bash
$ git clone https://github.com/guptavishakha14/Carpooling-Web-App.git
```

After this, enter the following commands to run the webserver:
```bash
$ python manage.py migrate
$ python manage.py runserver
```


---
## Technologies Used

### Django Framework

Django is a Python-based free and open-source web framework, which follows the model-template-view architectural pattern.

### Google APIs Used
* **Directions API** - It is used to display route between two points. Route similarity is inferred based on this to broadcast ride request to specific drivers.
* **Distance Matrix API** - It is used to get distance between two points. This is used to decide fare of ride.
*  **Geocoding API** - It is used to convert a place name(For eg: Central Park, New York) to its corresponding coordinates(latitude and longitude). 
*  **Maps JavaScript API** - The API is used to make calls to different APIs using JavaScript.
*  **Places API** - The API is used to get suggestions of places when user types a string.

### Jquery

jQuery is a JavaScript library designed to simplify HTML DOM tree traversal and manipulation, as well as event handling, CSS animation, and Ajax. 

### Javascript

JavaScript, often abbreviated as JS, is a programming language that conforms to the ECMAScript specification. JavaScript is high-level, often just-in-time compiled, and multi-paradigm. It has curly-bracket syntax, dynamic typing, prototype-based object-orientation, and first-class functions.

### Bootstrap

Bootstrap is a free and open-source CSS framework directed at responsive, mobile-first front-end web development. It contains CSS- and JavaScript-based design templates for typography, forms, buttons, navigation, and other interface components.

### Python

Python is an interpreted, high-level, general-purpose programming language.

### Python Google Maps API

The API is used to make calls to different APIs using Python.

---
## Authors

* [Vishakha Gupta](https://github.com/guptavishakha14)
* [Saurabh Fulshankar](https://github.com/saurabhfulshankar)
* [Kartiki Deshmukh](https://github.com/kartiki001)
* [Prajwal Patil](https://github.com/PrajwalP7295)

---

