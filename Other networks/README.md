This category contains various networks that didn't fit into any of the other categories. They are stored in the Pajek NET format.

These networks are:
- **athletes_organizations** - A network of Slovenian athletes. The vertices represent athletes, which are connected if they are part of the same sports club/organization. This is an undirected graph.
- **athletes_competitions** - A network of Slovenian athletes. The vertices represent athletes, which are connected if they took part in the same competition. This is an undirected graph.
- **athletes_both** - A network of Slovenian athletes, which combines the criteria of the networks *athletes_organizations* and *athletes_competitions*. This is an undirected graph.
- **faculty** - A network of faculty and other employees of the University of Ljubljana, Faculty of Computer and Information Science in the year 2021. The vertices represent employees and are connected if the two employees are part of the same laboratory, work in the same room, participate in the same course or have participated in the same project. This is an undirected graph
- **flights_cargo_04-20** - A network which provides Slovenian flight data for the years 2004-2020. Vertices represent countries and edges represent cargo being flown to or from these countries to Slovenia. This is a directed graph. The edge weights represent total tonns of cargo.
- **flights_passengers_04-20** - A network which provides Slovenian flight data for the years 2004-2020. Vertices represent countries and edges represent passengers being flown to or from these countries to Slovenia. This is a directed graph. The edge weights represent total numbers of passengers.
- **LPP** - A network of the bus public transport in the city of Ljubljana: "Ljubljanski Potniški Promet." The Vertices represent bus stops, which are connected if a bus line goes from one stop to the other. This is a directed graph.
- **railways** - A network of the schema for the Slovenian railway network. This is an undirected graph.
- **startups** - A network of Slovenian startups that are part of the *Start:up Slovenia* platform. The vertices represent individual startups which are connected if they are part of the same *Start:up Slovenia* project. This is an undirected graph.

Basic statistics for the networks are gathered in the following table:
| Network                  | Vertices | Edges   |
|--------------------------|----------|---------|
| faculty                  | 216      | 1800    |
| flights_cargo_04-20      | 63       | 105     |
| flights_passengers_04-20 | 71       | 133     |
| LPP                      | 507      | 1085    |
| railways                 | 78       | 79      |
| athletes_both            | 7837     | 263.742 |
| athletes_organizations   | 7837     | 118.195 |
| athletes_competitions    | 7837     | 172.570 |
| startups                 | 262      | 16.816  |

