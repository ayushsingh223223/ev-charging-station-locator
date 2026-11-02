# EV Charging Station Locator

A web/mobile application that helps electric-vehicle (EV) users find, filter and navigate to nearby charging stations. This repository holds the software engineering documentation and design models for the project.

## Project summary

- Detect or select the user's location
- Search for charging stations within a radius
- Filter by connector type and availability, and sort by distance
- View station details (address, connectors, charging speed, availability)
- Navigate to a selected station
- Booking and payment, ratings and reviews, and admin station management (shown in the models; outside the MVP in the SRS)

## Contents

| Document | Description |
|---|---|
| [docs/01-Software-Requirements-Specification.docx](docs/01-Software-Requirements-Specification.docx) | Software Requirements Specification (IEEE format), v1.0 |
| [docs/02-Use-Case-Diagram.docx](docs/02-Use-Case-Diagram.docx) | Use case diagram, actor roles, and precondition, postcondition and function of each use case |
| [docs/03-Class-Diagram.docx](docs/03-Class-Diagram.docx) | Identified classes, strong and weak class classification, and the class diagram |
| [docs/04-Activity-Diagram.docx](docs/04-Activity-Diagram.docx) | Swimlane activity diagrams of the main workflows |
| [docs/05-Data-Flow-Diagram.docx](docs/05-Data-Flow-Diagram.docx) | Data flow diagrams: Level 0, Level 1 and Level 2 |
| [docs/06-Sequence-Diagram.docx](docs/06-Sequence-Diagram.docx) | Sequence diagrams: login and search, details and navigation, booking and payment |
| [docs/07-State-Transition-Diagram.docx](docs/07-State-Transition-Diagram.docx) | State transition diagrams: charging slot, booking and payment |

## Diagram images

The `diagrams/` folder contains every diagram as a PNG so it can be viewed directly on GitHub:

- `diagrams/use-case-diagram.png`
- `diagrams/class/`: class diagram (and its Graphviz source)
- `diagrams/activity/`: four activity diagrams
- `diagrams/dfd/`: Level 0, Level 1 (three parts) and Level 2 (search, booking)
- `diagrams/sequence/`: three sequence diagrams
- `diagrams/state/`: charging slot, booking and payment states

## Team

Ayush Pandey, Ayush Shrivastava, Ayush Singh, Ayush Singh
