+++
# Date this page was created.
date = 2016-04-27T00:00:00

# Project title.
title = "Siesta"

# Project summary to display on homepage.
summary = "Winner of the Frank Jarrett Prize in machine design – A smart drink dispenser."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "siesta.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["machine-design", "manufacturing", "control", "electronics"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++
![Siesta in demonstration](/img/siesta_irl.jpg)
![Siesta's brains](/img/siesta_brain_view.jpg)

Siesta, a touchscreen-based drink dispenser, was completed with a group of four other students for the senior Mechatronics Design course at Berkeley (ME102B). Our team decided on creating an automatic drink dispenser capable of payment tracking for billing purposes within an internal database and dispensing up to three refrigerated drinks and one hot drink of desired volumes. The inspiration for this project came when one teammate realized there was a regular shortage of coffee for him and his department due to other departments stealing the inventory. Thus, we realized the benefit of creating a versatile drink dispenser for office use that is able to track and bill people’s personal or department’s usage.

Upon the design of the project, our team decided to place a high emphasis on final-product aesthetics and presentation due to the implicit trend of previous projects looking like prototypes. Siesta was made of bent aluminum sheet metal, acrylic, and a 3D printed cup holder with all other internals encased within the aluminum casing. Refrigeration of the drinks was made possible by using two peltier units coupled with an insulating casing, which were capable of maintaining a steady state temperature of 5ºC. Heating of the drink was made possible by using a generic heating element encased in a thermally insulated thermos. The custom-made GUI was displayed on a 7” touchscreen display and was powered by a Raspberry Pi using Kivy, a Python library. The drinks were dispensed by diaphragm pumps controlled by an Arduino Mega.

![Electrical schematic](/img/siesta_schematic.png)

I was in charge of writing the controllers to regulate the volume flow of the pumps, the temperature of the hot drink, and establishing secure serial communication with the Arduino and the Raspberry Pi’s GUI along with all hardware associated with these controllers. In addition, I aided with the manufacturing of the outer casing and the manifolds (not shown) to prevent leakage to a high tolerance.

![Me, demoing](/img/siesta_demo.jpg)

For the final expo, Siesta functioned flawlessly with no errors or issues and was ultimately selected to receive the Frank Jarrett Machine Design Prize as the most outstanding ME102B project. For more information and images, visit [the website](https://siesta-berkeley.weebly.com/). {{< youtube U31IIIBJkOY >}}

*Learning outcomes of this project include: Team communication skills, time management (deadline) responsibilities, electrical systems integration, manufacturing and design techniques.*
