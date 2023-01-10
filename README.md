# Community Science Traffic Counter

## Objective 


Develop a traffic counter to collect and store real time traffic volume and composition
data. The counter must be easily deployed and maintained at community scientist locations 
(e.g. residences, community halls, schools).


## Motivation

The Tomorrow Foundation for a Sustainable Future (TF), an Edmonton environmental
charity, has a focus on creating projects that are grounded in the collection of 
data using community science. Currently they have a project to install air quality 
monitors at community locations, in conjunction with the Alberta Capital Airshed (ACA). 
The TF would like to add further context to the air quality data being collected 
by gathering traffic data at the same location.

## Most Suitable Background for the Project


| Engineering Physics             | 2 |
|---------------------------------|---|
| Electrical Engineering          | 2 |
| Computer Engineering            | 1 |
| Computer Engineering – Software | 3 |

## Description

- The challenge is to create a traffic counter that is low-cost, can be easily 
installed, and is easily maintained by community members who may not have technical 
knowledge. The traffic counter shall count all traffic passing a specific location, 
and be able to distinguish between motorbikes, cars, trucks and bicycles. The 
location is likely to be either a community hall or a community member’s residence, 
and so will have power and WiFi available, and the computer can be installed inside, 
if the camera is outside and functional (security and extreme temperatures will be 
a consideration). 
- The expected outcome is a prototype of the counter, including instructions showing 
consideration of installation procedure/ requirements, as well as future operation 
and maintenance (for at least one year). The TF has developed a prototype already 
which can be used to build upon (test for suitability, or otherwise propose 
something new).
- A trade study to investigate viable platforms optimized for size, weight, and power 
that provide real-time performance of the functional and performance requirements 
is highly desired.

## Functional and Performance Requirements / Objectives

1. Real time identification and counting of different types of traffic (cars, 
trucks, motorbikes) - data
2. Collects data and stores it in the cloud for at least one year
3. Can be installed (connect to power and WiFi) in a typical residence with little 
to no maintenance (ease of operation and maintenance is a factor, including e.g. 
what happens if the community member changes their WiFi password)
4. Additional consideration of data visualization

## Specifications / Constraints

- The final prototype design should have the following elements:
  1. Connection to power supply
  2. Connection to WiFi
  3. Ability to upload data to the cloud
  4. Outdoor mountable camera
  5. May be based on the original project done by the TF, but not necessarily
    - A proposal for a different approach can be entertained.

## Information Resources / Links

### Codebase and Libraries

- The original prototype developed by TF referred to the following links for the open source code:
  - [opendatacam](https://github.com/opendatacam/opendatacam)
  - [Using opendatacam and balena to quantify the world with AI](https://www.balena.io/blog/using-opendatacam-and-balena-to-quantify-the-world-with-ai/)

### Equipments Used in Original Prototype

- [Outdoor Camera (suggested)](https://www.amazon.ca/Wyze-Wireless-Camera-Android-Version/dp/B076H3SRXG)
- [Box (installed inside house) $35.99](https://www.amazon.ca/Waveshare-Case-Specialized-Jetson-Nano/dp/B08PBXVP1X/ref=sr_1_1?crid=YHJDUN0T7IKJ&keywords=waveshare+metal+case+specialized+for+jetson+nano&qid=1662506335&s=electronics&sprefix=waveshare+metal+case+specialized+for+jeston+nano%2Celectronics%2C112&sr=1-1)
- [Memory Card $12.99](https://www.amazon.ca/SanDisk-Ultra-microSDHC-Memory-Adapter/dp/B08GYBBBBH/ref=sr_1_3?crid=234E0L02LOHPX&keywords=sandisk+64+gb&qid=1662506386&s=electronics&sprefix=sandisk+64+gb%2Celectronics%2C116&sr=1-3)
- [Power supply $18.99](https://www.amazon.ca/Waveshare-Power-Supply-Applicable-Jetson/dp/B07X8P1LFD/ref=sr_1_1?crid=33JOO7XZK2FUW&keywords=waveshare+power+supply+applicable&qid=1662506462&s=electronics&sprefix=waveshare+power+supply+applicable%2Celectronics%2C124&sr=1-1)
- [Wireless NIC module $28.99](https://www.amazon.ca/Waveshare-AC8265-Wireless-Supports-Bluetooth/dp/B07SGDRG34/ref=sr_1_2?crid=3AUQ6AZP6XMLV&keywords=waveshare+wireless+NIC+Module&qid=1662506516&s=electronics&sprefix=waveshare+wireless+nic+module%2Celectronics%2C109&sr=1-2)
- [Developer Kit Board $799](https://www.amazon.ca/NVIDIA-Jetson-Developer-Computer-Development/dp/B07SHF9V4J/ref=sr_1_2?crid=1NB1S6BM3OEWB&keywords=jetson+nano+developer+kit+single+board+computer&qid=1662506594&s=electronics&sprefix=jetson+nano+developer+kit+single+board+computer%2Celectronics%2C125&sr=1-2)
  - or [Developer Kit Board $150](https://www.sparkfun.com/products/16271#reviews)

## Prototyping/Testing Resources

- No specific testing resources required other than power and WiFi, and a location 
that has traffic that can be counted. Testing may be preferred in a community scientist 
location, if that can be arranged.

## Intellectual Property Restrictions

- Note: Public presentation and, hence, disclosure is a course requirement.
  - All results and intellectual property created will be owned by the sponsor with 
  the student capstone group having the right to use same royalty-free (written 
  agreement required).
  - The sponsor reserves the right to open source the project.
