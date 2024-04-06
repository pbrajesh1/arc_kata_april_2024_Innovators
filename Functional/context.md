# FishWatch

## Company Overview
Livestock Insights Incorporated is a company headquartered in Scotland, but operating globally. Their main service offering, Fishy Watch, is used by Fish Farmers around the world to monitor their fish, and the fish farms in general. It is able to collect information about individual fish, water quality, and weather information. Fish farmers use this information to understand the health of their livestock, check for signs of parasites and disease, and work out the best time to harvest.

## Requirements
Each customer of Fish Watch may operate a number of fish farms in different geographical locations. Some customers might have a single farm, but the biggest clients have over a hundred. Each farm is split into different enclosures where the fish are kept. A small farm might have as few as ten enclosures, large farms may have a thousand or more. The biggest farms might have over a million fish.

There are water monitors in each enclosure which capture water quality information including PH, temperature, salinity, oxygen levels and other factors. Underwater cameras are positioned in each enclosure which can get a general view of fish health, looking at size, activity, and whether parasites are detected. A beta feature is live where individual fish can be identified via fish-ual recognition, to monitor the health and lifecycle of an individual fish.

Farmers need to be able to see the collected information in dashboards which they can customise. They also need to be able to specify thresholds at which alerts should be triggered - this could be simple things like a PH going out of bound, but could also involve advanced warnings of adverse weather events which are expected. Farmers track information about the fish harvested from each farm, and this information together with the raw data being collected should be used to build a model of what factors produce good harvests.

Each farm may have a variety of different fish species. For large customers, they will want to be able to drive insights across a number of farms. It’s vital that alerts be generated in a timely manner - a sharp degradation in water quality or adverse weather event could have massive implications if the farmer doesn’t have enough warning. It’s assumed that more detailed information about fish behaviour and water quality etc will become richer over time as we are able to deploy more powerful devices.

## Other Considerations
Fish Watch needs to be accessible from a number of devices, including rugged industrial devices used on the sea during harvest. Fish farms are often in remote locations, where cellular signal may be poor. You can assume that the hardware devices to capture water information and detect fish behaviour already exist, but you need to define how these devices will send the information to the system. Livestock Insights Inc. is considering providing similar capabilities to cattle, and also allowing aquariums to use the system to look after fish health.

[Previous Page](../README.md) | [Next Page](./DriversGoals.md) 
