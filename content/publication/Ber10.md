+++
title = "Automating Acceptance Tests for Sensor- and Actuator-based Systems on the Example of Autonomous Vehicles"
abstract = "In projects dealing with autonomous vehicles which are driving in different contexts like highways, urban environments, and rough areas, managing the software's quality for the entire data processing chain of sensor- and actuator-based autonomous systems is increasingly complex. One main reason is the early dependency on all sensor's raw data to setup the data processing chain and to identify subsystems. These sensors' data might be extensive, especially if laser scanners or color camera systems are continuously producing a vast amount of raw data. Moreover, due to this dependency the sensors' setup including their respectively specified mounting positions and calibration information is also necessary to gather real input data from real surroundings' situations of the system. This is even more important before actually starting to integrate independently developed subsystems for carrying out tests for the entire data processing chain.

To reduce this dependency and therefore to decouple tasks from the project's critical path, an approach is outlined in this thesis which was developed to support the software engineering for sensor- and actuator-based autonomous systems. This approach relies on customer's requirements and corresponding customer's acceptance criteria as well as the decoupling of the software engineering from the real hardware environment to allow appropriate system simulations.

Based on the customer's requirements, formally specified scenarios using a domain specific language are derived which are used to provide surroundings and suitable situations for a sensor- and actuator-based autonomous system. From these formally specified surroundings, the required input data is derived for different layers of a sensor data processing system to generate actions within the system's context. This input data itself depends on a given sensor model to compute its specific raw data. Amongst others, on the example of laser scanners and camera systems, algorithms using modern graphical processing units are outlined to generate the required raw data even for complex situations.

To realize the aforementioned aspects, a development environment is necessary consisting of tools for modeling and working with instances of a domain specific language. Furthermore, a software framework is required which provides easily usable and mature solutions for common programming requirements like synchronization for concurrent threads or communication in a high-level point of view. For relying on a consistent and homogeneous software framework for implementing the concepts, a highly portable and real-time-capable software framework for distributed applications was realized which was written entirely from scratch in strictly object-oriented C++. Moreover, this software framework also integrates the formally modeled input data derived from the specified requirements and the sensors' models to allow unattended system simulations to support the acceptance tests for subsystems or an entire system.

On the example of autonomous vehicles, the applicability of the approach and the software framework is demonstrated by implementing a vehicle navigation algorithm which uses a given digital map for finding the best route to a desired destination from an arbitrarily chosen starting point. This algorithm was developed considering the test-first-principle and is continuously evaluated by unattended and automatic software tests which are executed on a continuous integration system. Its implementation as well as its evaluation make use of the aforementioned concepts and algorithms. Therefore, the vehicle's surroundings were formally modeled together with its necessary sensors using the provided development tools and environment for performing and evaluating unattended system runs before the algorithm was put into operation on the real vehicle."
abstract_short = ""
publication_short = ""
publication = "Engineering"
authors = ["Berger, Christian"]
date = "2010-08-01"
image = ""
image_preview = ""
math = false
selected = false
url_slides = ""
url_project = ""
url_code = ""
url_pdf = "http://www.christianberger.net/Ber10.pdf"
url_video = ""
url_dataset = ""

+++