<!-- This is the markdown template for the final project of the Building AI course,
created by Reaktor Innovations and University of Helsinki.
Copy the template, paste it to your GitHub README and edit! -->

# SmartWasteAI

Final project for the Building AI course

## Summary

SmartWasteAI uses machine learning and sensor data to predict optimal garbage collection times and routes, reducing costs, emissions, and overflows in urban waste management systems.

## Background

Urban waste overflow and inefficient pickup routes are a major issue in many cities. Bins are either collected too often (wasting fuel and labor) or too late (causing hygiene issues).

This is how you make a list, if you need one:
* Overflowing public bins
* Inefficient pickup schedules
* Carbon emissions from waste trucks

My motivation: I live in a city where trash bins often overflow, causing bad smell and health risks. This idea could help municipalities become smarter and cleaner.

## How is it used?

Municipalities equip public trash bins with weight or fill-level sensors. The data is collected daily and used to train a machine learning model that predicts:
- When each bin will be full
- The best pickup route for trucks

The dashboard lets planners:
- View bins nearing capacity
- Get route suggestions
- Improve collection schedules

<img src="smartbin-map.png" width="400">

## Data sources and AI methods

- Sensor data from smart bins (simulated or open city data)
- Weather and public event schedules (affect fill rates)
- AI methods: Regression for bin fill predictions, K-means or route optimization, reinforcement learning for scheduling
- Visualization: Matplotlib/Plotly in Python

Example data source:
[Open City Sensor Data](https://data.gov)

| Feature        | Source             |
|----------------|--------------------|
| Fill-level     | IoT sensors        |
| Location       | GPS/Bin mapping    |
| Event calendar | Open city datasets |

## Challenges

This project does _not_ solve:
* Areas without sensor infrastructure
* Multi-bin sorting (plastic, glass, etc.)
* Unexpected events like illegal dumping

Ethical considerations:
- Data privacy of location data
- Ensuring open access to algorithm recommendations

## What next?

To move forward:
- Partner with a local municipality
- Add real-time dashboard
- Deploy prototype for 3–6 months
- Gather feedback and iterate

## Acknowledgments

* Inspired by the Elements of AI course
* Idea shaped by waste issues observed in Rabat, Morocco
* Icons from [Flaticon](https://www.flaticon.com/)
* Image credits: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
