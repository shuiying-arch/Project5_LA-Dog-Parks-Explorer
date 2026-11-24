# Project5_LA-Dog-Parks-Explorer
SSCI 591 Project 5 - Cloud Web GIS Dog Parks Explorer

## Project Overview

LA Dog Parks Explorer is a Web GIS application that helps dog owners find parks with dog park facilities across Los Angeles County. This project extends my Project 3 application and deploys it using AWS Amplify.

## Live Application

[Open LA Dog Parks Explorer](https://main.d38p8blvdb90ye.amplifyapp.com)

## New Features

- Search dog parks by park name.
- Filter dog parks with restrooms.
- Display the number of matching parks.
- Reset the map and search results.
- Improve the mobile-friendly interface.

## Technologies Used

- HTML, CSS and JavaScript
- ArcGIS Maps SDK for JavaScript
- ArcGIS REST Services
- GitHub
- AWS Amplify

## Cloud Deployment

The application is hosted on AWS Amplify and connected to the main branch of my GitHub repository. When I update the code on GitHub, AWS Amplify automatically redeploys the application.

## Testing and Improvement

I tested the application on a desktop browser, an incognito browser and a mobile device using cellular data. I also shared the application with another user for testing.

During mobile testing, I found that the map legend was too large and covered part of the park information popup. I updated the code to move the legend below the map on mobile devices.

## Cost Estimation

The measured data transfer from AWS is approximately 3.0 kB per visit.

| Daily Visits | Monthly Visits | Estimated Monthly Cost |
| --- | --- | --- |
| 100 | 3,000 | $0.06 |
| 100,000 | 3,000,000 | $1.41 |

The estimates use standard AWS pricing before credits and assume two three-minute builds per month. Data transfer is the main cost that increases with website traffic.

My AWS Free Plan has $120 in remaining credits. I also created a $1 budget to monitor AWS costs.

## Data Source and References

- [Los Angeles County Parks and Open Space Dataset](https://services.arcgis.com/RmCCgQtiZLDCtblq/ArcGIS/rest/services/Countywide_Parks_and_Open_Space___(Public_-_Hosted2)/FeatureServer/0)
- [ArcGIS Maps SDK for JavaScript](https://developers.arcgis.com/javascript/latest/)
- [AWS Amplify Pricing](https://aws.amazon.com/amplify/pricing/)
- [Original Project 3 Application](https://shuiying-arch.github.io/Project3_LA-Dog-Parks-Explorer/)
