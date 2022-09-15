## Challenge - Connected Vehicles for Efficiency and Sustainability


### Optimizing operations for fleets is a big challenge for fleet managers. Logistic companies are constrained by a small margin and any decision should be driven by cost and the company strategy, e.g., in sustainability.
### Use your skills to build a recommender system that helps a fleet manager to optimize the logistics operations. Collaborate with us and help increase the efficiency and sustainability of transport service. Let's do it!

The task of a fleet manager is to make sure all resources such as vehicles, and drivers have been used in an optimum way. It is often a challenge for them to access a powerful intelligent tool as a support system to help them to make the best decision. Often times there are multiple factors which play a role and would require a sophisticated intelligence to handle and analyze and provide insights. Among all, few factors to name here are: drivers’ behaviors, driving situations (highway, city, weather, geolocation, etc.), vehicle condition and type, vehicles’ fuel/battery status. Here we want you to build a solution to suggest the best combination of drivers and vehicles and driving situation for the fleet operation efficiency.

We challenge you to create a software that would help a fleet manager to be operate the fleet in a most efficient and sustainable way: Invent an intelligent algorithm for efficient operation prediction (fuel consumption as an example), paired with a frontend for visualising and recommending a best use of resources for a fleet.

### Background 

Our [Digital Fleet Management Solution](https://www.zf.com/products/en/cv/fleet/fleet_emea.html) develops and commercializes digital transport services for fleets and logistics sector. We are a global full solution provider of truck, driver, trailer, cargo and subcontractor management.

<img src="https://user-images.githubusercontent.com/27730528/189535145-941e9331-1e85-4e05-b76d-bb4c5bc4ac20.png"  width="700">

The component of the commercial vehicles (truck & trailers) are connected and continuosly transmit data to the cloud over the status and their condition:

<img src="https://user-images.githubusercontent.com/27730528/189535243-a207c9af-ce93-4bca-ae44-7c28d1299678.png"  width="700">


Let's describe it in more details in the following what we mean by Fleets' efficiency in operation.

Commercial vehicle fleets (heavy duty vehicles for Cargo transport) are becoming ever more connected, allowing for collection of data sources such as fuel consumption, driving condition, driver behaviour, braking events, location, etc., to name just a few.
The cost of this increased connectivity eats into the already-small margins of most fleets, but how could be used to a fleet's advantage?

The folllowing is a schematic image of fuel/energy consumption distribution by multiple drivers: 

<img src="https://user-images.githubusercontent.com/27730528/189534561-e959164e-702c-4b4f-b84e-c6aab2b1a373.png"  width="500">

As shown, driving behaviour is one of the important driver to the fuel consumption. Every fleet manager would like to have a such a picture according to the historical fleet operations and optimized the efficiency and sustainability. The main challenge is to provide enough evidence to the fleet manager to decide based on the data in the past. Hence the fleet manager would be able to optimize his/her resources, i.e., connect a right driver to a right trip and vehicle. 


### Problem statement

*Question:* How might we help the fleet manager use their fleet data to reduce their operating costs and improve sustainability? 

*Challenge:* Develop a concept that utilises driving insights to optimise the operation of a fleet for its owner.

*Hints:*
- Start with a clear business case/idea.
- Focus on identifying how connecting vehicle data to alternative data sources can add value.


### Data provided

- Description of data columns provided in excel format (Description_data_ZF.xlsx).
- Vehicle fuel consumption data, aggregated at trip-based level, i.e., how much fuel consumed during various trip missions (defined by ignition on/off) of the vehicle (Export_data_ZF.csv).
- Dashboard available in Power BI (ZF_powerbi.pbix).

The Dataset contains >15000 trips, 43 vehicles, and 178 drivers (available in power bi data table sheet as well).


### Goal

In the power bi dashboard we have provided some insight on various factors playing a role for the fuel consumption at a descriptive level. The first goal is try to clasify the features which are contributing on driving behavior for example.
<img src="https://user-images.githubusercontent.com/113338125/190188820-69cc40a3-cc4a-4172-89f7-d1e484bdb34e.png"  width="700">


The trips (vehicle missions) can be clustered as we have shown in the insight tab based on varios feature and a so-called K-means metric:
<img src="https://user-images.githubusercontent.com/113338125/190189748-d251054f-f90a-412c-8868-8d422b6f633f.png"  width="800">


One of the goal here could be to build up a model to demonstrate how much driving behavior contributes positively on classifying the trips or drivers. Therefore one can estimate the contribution of the driving behavior on the fuel consumption.


### Our expectation

- Presentation with a clear problem statement & solution definition (a business opportunity potentially supported by market demand).
- Provide Illustration of results as much as possible.
- Mockup/wireframe of digital solution for a fleet manager with a prescriptive / decision making feature.

Design a mockup of business solution using insights from the data provided. The solution should serve a fleet manager to optimize the fleet operation.


### Downloads
Downloads will be made available during the workshops on Friday, Sept 16. Stay tuned!

We look forward to working with you at the HackZurich 2022!

You have questions, ideas for your own project, or just want to chat with us? Reach out on DISCORD channel #19-zf or directly at our booth.
