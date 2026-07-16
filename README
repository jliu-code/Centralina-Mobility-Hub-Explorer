# Centralina Mobility Hub Explorer

An interactive GIS planning tool for exploring where mobility hubs could take root in communities across the Centralina region.

[**Navigate to the Mobility Hub Explorer**](https://www.connect-beyond.com/key-initiatives/mobility-hubs/)

## Overview

Mobility hubs are places where transportation options, community destinations, public spaces, and supporting services come together. They can range from major transit stations to smaller community locations that improve connections between people and places.

The **Mobility Hub Explorer** helps planners, local governments, community partners, and other stakeholders examine the conditions surrounding a potential mobility hub. Users can select a location, create a half-mile study area, and explore transportation infrastructure, destinations, land use, demographic information, and other community characteristics within that area.

The application grew from the **CONNECT Beyond regional mobility initiative** and the **Regional Mobility Hub Implementation Strategy**. Initial pilot concepts were developed with Belmont, Huntersville, Kannapolis, and Lincoln County.

## Key Features

* Select a potential mobility hub location directly from the map.
* Generate a half-mile radius around the selected location.
* Identify map features that intersect the study area.
* Explore transportation services and infrastructure.
* Review nearby destinations and community assets.
* Examine trails, greenways, sidewalks, and other active transportation facilities.
* Explore land-use and demographic context.
* Toggle web maps, basemaps, and informational pop-ups.
* Support planning conversations using a consistent regional data framework.
* View locally tailored mobility hub concepts and supporting information.

## Intended Users

The Mobility Hub Explorer is designed for:

* Local and regional planners
* Transportation agencies
* Local governments
* Community and economic development organizations
* Elected officials
* Consultants and technical staff
* Funding and implementation partners
* Community stakeholders and residents

## Example Use Cases

The application can support such as:

* Early screening of potential mobility hub locations
* Mobility hub planning workshops
* Community and stakeholder engagement
* Transportation and land-use coordination
* Review of nearby mobility services and destinations
* Comparison of different hub locations
* Identification of potential infrastructure gaps
* Preparation of grant applications and planning studies
* Communication of mobility hub concepts to decision-makers

## Using the Application

1. Open the [Mobility Hub Explorer](https://d9dzqszio0qvu.cloudfront.net/).
2. Navigate to the community or a general location you want to examine.
3. Place or select a potential mobility hub center with a pin.
4. Create a half-mile study area and run analysis.
5. Review the transportation, destination, land-use, and community information returned for the study area.
6. Use the layer list, legend, pop-ups, and other map controls to investigate individual features.
7. Reset or relocate the study area to compare another location.

## Application Architecture
The exported Experience Builder application is hosted as a static web application in Amazon S3 and delivered through Amazon CloudFront. Map content and GIS services are managed through ArcGIS Online.

## Technology Stack

* **Application framework:** ArcGIS Experience Builder Developer Edition
* **Programming language:** TypeScript
* **User interface:** React and Jimu UI
* **Mapping:** ArcGIS Maps SDK for JavaScript
* **GIS content management:** ArcGIS Online
* **Map configuration:** ArcGIS Web Maps
* **Data services:** ArcGIS hosted feature layers and reference services
* **Static hosting:** Amazon S3
* **Content delivery:** Amazon CloudFront
* **Version control:** Git and GitHub

## Custom Functionality

The project includes custom ArcGIS Experience Builder functionality for workflows that are not fully addressed by standard widgets.

### Location and Buffer Selection

The location-selection widget allows a user to identify a potential hub center and generate a half-mile study area around it.

Primary responsibilities include:

* Capturing the selected map location
* Creating a geodesic half-mile buffer
* Displaying the resulting study area
* Passing the study area to other application components
* Supporting reset and rerun workflows

### Spatial Analysis

The spatial-analysis widget evaluates configured GIS layers against the selected study area.

Primary responsibilities include:

* Running spatial intersection queries
* Selecting or filtering intersecting features
* Updating connected widgets and map displays
* Managing map extent and zoom behavior
* Supporting repeated analyses at different locations
* Communicating results through map symbols, pop-ups, summaries, and legends

## Data Categories

Depending on availability and community coverage, the application may include:

| Category              | Example Information                                                                     |
| --------------------- | --------------------------------------------------------------------------------------- |
| Transit               | Stops, routes, stations, microtransit, and park-and-ride facilities                     |
| Active transportation | Sidewalks, bicycle facilities, greenways, trails, and crossings                         |
| Road network          | Roads, intersections, and related transportation infrastructure                         |
| Destinations          | Schools, parks, libraries, civic facilities, employment centers, and community services |
| Land use              | Existing land use, development patterns, and activity centers                           |
| Demographics          | Population, households, employment, and selected socioeconomic characteristics          |
| Boundaries            | Municipal, county, census, and planning-area boundaries                                 |
| Mobility hub concepts | Candidate or pilot hub locations and concept information                                |

Data availability, completeness, update frequency, and geographic coverage vary by source. See raw_source_inventory for more information.

## Reporting Issues

When reporting an issue, include such as:

* A clear description of the problem
* Steps required to reproduce it (if helpful to describe the problem)
* The expected result
* The actual result
* Browser and operating system
* A screenshot or screen recording, when helpful
* The selected location or community
* The affected map layer or widget
* Relevant browser-console errors

Do not include passwords, private access tokens, or sensitive information in an issue.

## Contributing

Contributions should be submitted through a feature branch and pull request.

Recommended workflow:

```bash
git checkout -b feature/brief-description
git add .
git commit -m "Add brief description of change"
git push origin feature/brief-description
```

Before submitting a pull request:

* Test the application locally.
* Verify that custom widgets compile without errors.
* Test the primary location-selection and spatial-analysis workflows.
* Confirm that existing data sources remain connected.
* Document configuration or schema changes.
* Avoid committing generated files, credentials, or local configuration.
* Include screenshots for visible interface changes.

## Suggested GitHub Topics

```text
arcgis
arcgis-experience-builder
arcgis-online
gis
geospatial
typescript
react
mobility-hubs
transportation-planning
land-use-planning
regional-planning
spatial-analysis
```

## Acknowledgments

The Mobility Hub Explorer was developed to support implementation of mobility hub planning in the Centralina region.

The project builds on collaboration among:

* Centralina Regional Council
* Participating local governments
* State, local, and regional Transportation and planning partners
* Project consultants
* Esri and the ArcGIS platform

## Additional Resources

* [ArcGIS Experience Builder Developer Documentation](https://developers.arcgis.com/experience-builder/)
* [Experience Builder Installation Guide](https://developers.arcgis.com/experience-builder/guide/install-guide/)
* [Experience Builder Deployment Guide](https://developers.arcgis.com/experience-builder/guide/experience-deployment/)
* [Amazon CloudFront Documentation](https://docs.aws.amazon.com/cloudfront/)
* [Amazon S3 Documentation](https://docs.aws.amazon.com/s3/)
