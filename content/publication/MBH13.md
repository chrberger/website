+++
title = "Engineering the Hardware/Software Interface for Robotic Platforms - A Comparison of Applied Model Checking with Prolog and Alloy"
abstract = "Robotic platforms serve different use cases ranging from experiments for prototyping assistive applications up to embedded systems for realizing cyber-physical systems in various domains. We are using 1:10 scale miniature vehicles as a robotic platform to conduct research in the domain of self-driving cars and collaborative vehicle fleets. Thus, experiments with different sensors like e.g. ultra-sonic, infrared, and rotary encoders need to be prepared and realized using our vehicle platform. For each setup, we need to configure the hardware/software interface board to handle all sensors and actors. Therefore, we need to find a specific configuration setting for each pin of the interface board that can handle our current hardware setup but which is also flexible enough to support further sensors or actors for future use cases. In this paper, we show how to model the domain of the configuration space for a hardware/software interface board to enable model checking for solving the tasks of finding any, all, and the best possible pin configuration. We present results from a formal experiment applying the declarative languages Alloy and Prolog to guide the process of engineering the hardware/software interface for robotic platforms on the example of a configuration complexity up to ten pins resulting in a configuration space greater than 14.5 million possibilities. Our results show that our domain model in Alloy performs better compared to Prolog to find feasible solutions for larger configurations with an average time of 0.58s. To find the best solution, our model for Prolog performs better taking only 1.38s for the largest desired configuration; however, this important use case is currently not covered by the existing tools for the hardware used as an example in this article."
abstract_short = ""
publication_short = ""
publication = "4th International Workshop on Domain-Specific Languages and models for ROBotic systems (DSLRob)"
authors = ["Mamun, Md Abdullah Al and Berger, Christian and Hansson, Jörgen"]
editors = ["Schlegel, Christian and Schultz, Ulrik Pagh and Stinckwich, Serge"]
date = "2013-11-01"
image = ""
image_preview = ""
math = false
selected = false
url_slides = ""
url_project = ""
url_code = ""
url_pdf = "http://arxiv.org/abs/1401.3985"
url_video = ""
url_dataset = ""

+++
