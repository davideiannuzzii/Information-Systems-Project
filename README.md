# Participium

Analysis and design of **Participium**, an information system for citizen participation in the management of urban environments for the Municipality of Turin. Project developed for the *Information Systems* course (a.y. 2025/26).

## About the system

Participium allows citizens to report problems and malfunctions in the city, such as potholes, architectural barriers, waste, broken streetlights and more, and to follow how those reports are handled by the public administration. The system is designed to be released as open-source software for all Italian public administrations. A similar existing system is [IRIS](https://iris.sad.ve.it/) in Venice.

### Main features

- **Reports**: registered citizens submit geolocated reports on a map of Turin, with title, description, category and 1 to 3 photos, with the option to stay anonymous.
- **Report lifecycle**: preliminary review by the Municipality's Organization Office, assignment to the competent technical office, and optional handling by external maintenance companies (with or without access to the platform).
- **Citizen updates**: in-platform notifications and emails at every state change, two-way messaging with municipal operators (also accessible by external chatbots), and the ability to follow other citizens' reports.
- **Statistics**: public statistics on reports per category and over time, plus a private administrator section with detailed breakdowns by state, type and reporter.

## Deliverables

| Deliverable | Description | Format |
|---|---|---|
| Conceptual model | UML class diagram (sections A-B-C) | PDF, XML |
| Process model | BPMN process diagram (sections A-B-C) | PDF, XML |
| Use case diagram | Summary and user-goal level, all sections | PDF, XML |
| Use case narratives | User-goal level narratives | PDF |
| Cost estimation | Use Case Points (UCP) comparing two development alternatives | XLSX |

Diagrams were modeled with **Signavio**.

## Cost estimation

The UCP estimate compares two development scenarios:

1. A team of five recent computer engineering graduates working full-time, led by an experienced analyst.
2. A team of ten experienced offshore developers working part-time (one-third of their time), plus a lead analyst based in Italy.

## Authors

- Davide Iannuzzi ([@davideiannuzzii](https://github.com/davideiannuzzii))
- Micaela Carianni
- Pasquale Gallo
- Manfredi Buscemi

## License

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0). See [LICENSE](LICENSE) for details.
