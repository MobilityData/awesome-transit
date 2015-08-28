# awesome-transit [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

##### A collection of awesome transit projects  :busstop: :bus::dash: :train::dash: :steam_locomotive::dash:

Have something to add or change? Open a [pull request](https://github.com/luqmaan/awesome-transit/pulls) or [issue](https://github.com/luqmaan/awesome-transit/issues).

------------------------------

### Table of Contents

- [Data](#data)
- [APIs](#apis)
- [Web Apps](#web-apps)
- [Native Apps (open source)](#native-apps-open-source)
- [Native Apps (closed source)](#native-apps-closed-source)
- [Visualizations](#visualizations)
- [Resources](#resources)
- [GTFS](#gtfs)
- [GTFS-realtime](#gtfs-realtime)
- [SIRI](#siri)

### Data

- [GTFS Data Exchange](http://www.gtfs-data-exchange.com/agencies) - Links to many transit agency GTFS datasets.
- [CapMetrics](https://github.com/scascketta/CapMetrics) - Historical vehicle locations for Austin's transit agency (CapMetro). Data is collected by [capmetricsd](https://github.com/scascketta/capmetricsd), a Go daemon.
- [National Transit Database](http://www.ntdprogram.gov/) - Information and statistics on the transit systems of the United States, run by the Federal Transit Administration.
- [Transitland](https://transit.land/) - A community-edited data service aggregating transit networks across metropolitan and rural areas around the world. Currently under development.
- [TransitFeeds](http://transitfeeds.com/) - An archive of public transit data for software developers, transit agencies, and more

### APIs

Software that provides an API to transit data.

- [Navitia.io](http://www.navitia.io/) - REST API for journey planning, stop schedules, isocrhons and lot more on US and EU. [Navitia](https://github.com/CanalTP/navitia) is the opensource engine behind the live API.
- [OneBusAway](http://onebusaway.org/) - A Java app that consumes GTFS and GTFS-Realtime (along with [other formats](https://github.com/OneBusAway/onebusaway-application-modules/wiki/Real-Time-Data-Configuration-Guide)) and turns them into an easy to use [REST API](http://developer.onebusaway.org/modules/onebusaway-application-modules/current/api/where/index.html).
- [TransiTime](http://www.transitime.org) - Java application that can consume raw vehicle positions and generate prediction times in formats such as GTFS-realtime.
- [pyBikes](https://github.com/eskerda/pybikes) - an API on worldwide bikeshare systems powering [CityBikes](http://api.citybik.es)  

### Web Apps

- [TransitScreen](http://TransitScreen.com) - Custom realtime displays of all local transportation choices
- [Instabus](http://instabus.org) - Realtime map of Austin's (CapMetro) public transit. Has no server/backend dependency at all and runs completely on GitHub pages.
- [Maryland MTA Real-time Vehicle Tracking](http://mtabustrack.herokuapp.com/)
- [OpenTripPlanner Client GWT](https://github.com/mecatran/OpenTripPlanner-client-gwt) - A Google Web Toolkit-based web interface for OpenTripPlanner
- [OpenTripPlanner.js](https://github.com/conveyal/otp.js) - A Javascript-based client for OpenTripPlanner
- [GTFS-realtime Alerts Producer Web Application](https://github.com/OneBusAway/onebusaway-service-alerts) - A Java-based web application for producing GTFS-realtime Service Alerts.
- [HRT BUS Web app](https://github.com/Code4HR/hrt-bus-api) - HRT Bus API publishes real time bus data from Hampton Roads Transit through an application programming interface for developers to make apps from it.
- [Transit-Map](https://github.com/vasile/transit-map) - Web app that animates vehicles (markers) on a map using the public transport timetables to interpolate their positions along the routes (polylines).
- [Bikeshare Map](http://bikes.oobrien.com/) - Status of all worldwide bikeshare stations
 
### Native Apps (open source)

- OneBusAway Apps - [Android](https://play.google.com/store/apps/details?id=com.joulespersecond.seattlebusbot) [*(source code)*](https://github.com/OneBusAway/onebusaway-android), [Fire Phone](http://www.amazon.com/gp/mas/dl/android?p=com.joulespersecond.seattlebusbot) [*(source code)*](https://github.com/OneBusAway/onebusaway-android), [iOS](https://itunes.apple.com/us/app/onebusaway/id329380089)  [*(source code)*](https://github.com/OneBusAway/onebusaway-iphone), [Windows Phone](https://www.microsoft.com/en-us/store/apps/onebusaway/9nblggh0cbd9) [*(source code)*](https://github.com/OneBusAway/onebusaway-windows-phone), [Windows 8](https://www.microsoft.com/en-us/store/apps/onebusaway/9wzdncrdm5pc) [*(source code)*](https://github.com/OneBusAway/onebusaway-windows8), [Google Glass GDK](https://github.com/OneBusAway/onebusaway-android/pull/219) [*(source code)*](https://github.com/OneBusAway/onebusaway-android/pull/219)
- [OpenTripPlanner Android](https://github.com/CUTR-at-USF/OpenTripPlanner-for-Android/wiki) - An Android app for [OpenTripPlanner](http://www.opentripplanner.org/)
- [OpenTripPlanner iOS](https://github.com/opentripplanner/OpenTripPlanner-iOS) - An iOS app for [OpenTripPlanner](http://www.opentripplanner.org/)

### Native Apps (closed source)

- [ally](http://allyapp.com/)
- [Transit App](http://transitapp.com/)
- [CityMapper](http://citymapper.com/)
- [Moovit](http://moovitapp.com/)
- [Tiramisu Transit](http://www.tiramisutransit.com/)
- [Ridescout](http://www.ridescout.com/)
- [TransLoc Rider](http://translocrider.com/) - Real-time transit maps for over 100 transit systems.

### Visualizations

- [Visualizing MBTA Data](http://mbtaviz.github.io/) - Interactive graphs that show how people use Boston's subway system.
- [MIT COAXS](http://mittransportanalyst.github.io/) - Co-creative Planning of Transit Corridors using Accessibility-Based Stakeholder Engagement (shows route scenarios using [OpenTripPlanner Analyst](http://www.opentripplanner.org/analyst/)).
- [TRAVIC Transit Visualization Client](http://tracker.geops.ch/) - Visualizes vehicles moving based on static GTFS data (and sometimes realtime data). Supports over 260 cities.  Github account for geOps organization is [here](https://github.com/geops).

### Resources

- [TransitWiki](http://www.transitwiki.org/) - A wiki for transit planners to find cost-effective strategies to improve transit service.
- ["Legacy AVL system? It's okay, join the club." by Kurt Raschke](https://kurtraschke.com/2015/01/legacy-avl-export) - Good discussion of options for transforming legacy AVL system data into the GTFS-realtime format.
- [APTA Policy Development and Research - Public Transportation Embracing Open Data](http://www.apta.com/resources/reportsandpublications/Documents/APTA-Embracing-Open-Data.pdf) - APTA's discussion of the benefits and challenges of open transit data (a short summary of the below TCRP report).
- [TCRP Synthesis 115 - Open Data: Challenges and Opportunities for Transit Agencies](http://onlinepubs.trb.org/Onlinepubs/tcrp/tcrp_syn_115.pdf) - A comprehensive report looking at the benefits and challenges of open transit data.

### GTFS

Software that makes it easy to consume GTFS data.

- [Mapzen GTFS](https://github.com/transitland/mapzen-gtfs) - A Python GTFS library that supports reading individual GTFS tables, or constructing a graph to represent each agency in a feed.
- [gtfsdb](https://github.com/OpenTransitTools/gtfsdb) - Python library for converting GTFS files into a relational database.
- [OneBusAway GTFS Modules](https://github.com/OneBusAway/onebusaway-gtfs-modules/wiki) - A Java-based library for reading, writing, and transforming public transit data in the GTFS format, including database support.
- [GTFS to SQL](https://github.com/TransitFeeds/GtfsToSql) - Parses a GTFS feed into an SQL database (used in [TransitFeeds.com](http://transitfeeds.com/))
- [SQL to GTFS](https://github.com/TransitFeeds/SqlToGtfs) - Convert an SQLite file generated with "GtfsToSql" back to a zipped GTFS file.
- [Go GTFS Parser](https://github.com/geops/gtfsparser) - A GTFS parsing library for Go
- [GTFS Feed Parser](https://github.com/OsmSharp/GTFS) - .Net/Mono implementation of a GTFS parser
- [Node-GTFS](https://github.com/brendannee/node-gtfs) - Loads transit data in [GTFS format](https://developers.google.com/transit/) from [GTFS Data Exchange](http://www.gtfs-data-exchange.com/), unzips it and stores it to a MongoDB database and provides some methods to query for agencies, routes, stops and times.
- [GTFS-viz](https://github.com/vasile/GTFS-viz) - Ruby script that converts a set of GTFS files into a SQLite database + GeoJSONs (needed by the [Transit Map](https://github.com/vasile/transit-map) web application)
- [GTFS-OSM-Sync](https://github.com/CUTR-at-USF/gtfs-osm-sync) - A Java tool for syncrhonizing data in GTFS format with [OpenStreetMap.org](http://www.openstreetmap.org/).
- [Transmodel and IFF to GTFS](https://github.com/bliksemlabs/bliksemintegration) - Imports and syncs (Transmodel) BISON Koppelvlak1, IFF (a format written by HP/EDS, somewhat similiar to ATCO CIF) to import timetables of the railway networks. The internal pseudo-NETeX datastructure allows to export to GTFS and there are proof-of-concepts to export to other formats such as NETeX, GTFS and IFF.
- [Open-Transport SYNTHESE Convertors](https://github.com/Open-Transport/synthese/wiki) - Converts French-Transmodel, SIRI, NETeX, HAFAS, HASTUS, VDV452, and more.
- [Chouette](http://www.chouette.mobi/) - Converts French-Transmodel, SIRI, NETeX. See Chouette.mobi website for more info.

### GTFS-realtime

- [gtfs-realtime-bindings](https://github.com/google/gtfs-realtime-bindings) - The official bindings for Java, .NET, Node.js, Python, and Ruby generated from the official [GTFS-realtime protocol buffer specification](https://github.com/google/gtfs-realtime-bindings/blob/master/gtfs-realtime.proto).
- [gtfsrdb](https://github.com/mattwigway/gtfsrdb) - A Python tool that supports reading and archiving GTFS-realtime feeds into a database
- [GTFS-realtime to SQL](https://github.com/TransitFeeds/GtfsRealTimeToSql) - Parses a GTFS-RealTime feed into an SQL database (used in [TransitFeeds.com](http://transitfeeds.com/))
- [GTFS-realtime Validator](https://github.com/CUTR-at-USF/gtfs-realtime-validator) - A Java-based tool that validates GTFS-realtime feeds
- [GTFS-realtime Exporter](https://github.com/OneBusAway/onebusaway-gtfs-realtime-exporter/wiki) - A Java-based tool that assists in producing and sharing a GTFS-relatime feed.
- [GTFS-realtime Alerts Producer Demo](https://github.com/OneBusAway/onebusaway-gtfs-realtime-alerts-producer-demo/wiki) - A Java-based demo project for producing GTFS-realtime Service Alerts.
- [GTFS-realtime Alerts Producer Web Application](https://github.com/OneBusAway/onebusaway-service-alerts) - A Java-based web application for producing GTFS-realtime Service Alerts.
- [GTFS-realtime TripUpdates & VehiclePositions Producer Demo](https://github.com/OneBusAway/onebusaway-gtfs-realtime-trip-updates-producer-demo/wiki) - A Java-based demo project for producing GTFS-realtime TripUpdates (estimated arrivals) and Vehicle Positions.
- [GTFS-realtime Vehicle Positions Consumer/Visualizer Demo](https://github.com/OneBusAway/onebusaway-gtfs-realtime-visualizer/wiki) - A Java-based demo project for consuming a GTFS-realtime Vehicle Positions feed and displaying this info on a map.
- [SIRI to GTFS-realtime](https://github.com/OneBusAway/onebusaway-gtfs-realtime-from-siri-cli/wiki) - A Java-based command-line utility to convert from the [SIRI format](http://user47094.vs.easily.co.uk/siri/) to GTFS-realtime
- [OrbCAD SQL Server to GTFS-realtime](https://github.com/CUTR-at-USF/HART-GTFS-realtimeGenerator/wiki) - A Java-based command-line utility that extracts vehicle positions and trip updates information from an OrbCAD SQL Server and exports them to the GTFS-realtime TripUpdates and VehiclePositions formats.
- [NextBus API to GTFS-realtime](https://github.com/OneBusAway/onebusaway-gtfs-realtime-from-nextbus-cli/wiki) - A Java-based command-line utility to convert from the [NextBus API format](http://www.nextbus.com/xmlFeedDocs/NextBusXMLFeed.pdf) to GTFS-realtime.
- [Syncromatics API to GTFS-realtime](https://github.com/CUTR-at-USF/bullrunner-gtfs-realtime-generator) - A Java-based command-line utility to convert from the [Syncromatics API](http://www.syncromatics.com/) format to GTFS-realtime TripUpdates and VehiclePositons.
- [KV6,15,17, and ARNU to GTFS-realtime](https://github.com/bliksemlabs/bliksemintegration-realtime) - Java-based tool to process incoming KV6,15,17 and ARNU and match them to static transit data present in a RID integration database. It then proceeds to export this data as ARNU RITinfo, GTFS(realtime) and KV78turbo
- [WMATA BusPositions API to GTFS-realtime](https://github.com/kurtraschke/wmata-gtfsrealtime) - Java-based tool to convert from WMATA's [BusPositions API](https://developer.wmata.com/docs/services/54763629281d83086473f231/operations/5476362a281d830c946a3d68) and Alert RSS feeds from [MetroAlerts](http://www.wmata.com/rider_tools/metro_service_status/rail_bus.cfm?) to GTFS-realtime TripUpdates, VehiclePositions, and Alerts feeds.
- [SEPTA API to GTFS-realtime](https://github.com/kurtraschke/septa-gtfsrealtime) - Java-based tool to convert [SEPTA's](http://www.septa.org/) [real-time bus and rail data](http://www3.septa.org/hackathon/) to GTFS-realtime
- [CTA API to GTFS-realtime](https://github.com/kurtraschke/ctatt-gtfsrealtime) - Java-based tool to convert [CTA's](http://www.transitchicago.com/) [Train Tracker data](http://www.transitchicago.com/developers/traintracker.aspx) to GTFS-realtime.
- [Detroit DOT to GTFS-realtime](https://github.com/prashtx/ddot-avl) - Extract real-time info from [DDOT's](http://www.detroitmi.gov/How-Do-I/Locate-Transportation/Bus-Schedules) TransitMaster installation (database) and convert to GTFS-realtime
- [Live Transit Event Trigger](https://github.com/ipublic/live_transit_event_trigger) - Extracts data from [Ride On's](http://www.montgomerycountymd.gov/dot-transit/) OrbCAD database and export as GTFS-realtime.
- [SoundTransit to GTFS-realtime](https://github.com/bdferris/onebusaway-sound-transit-realtime) - Convert text file feed from [Sound Transit](http://www.soundtransit.org/) to GTFS-realtime
- [Civic Transit](https://github.com/jestin/CivicTransit) - Screen-scrapes [KCATA’s](http://www.kcata.org/) TransitMaster WebWatch installation to produce a GTFS-realtime feed.
- [GTFS-realtime Munin Plugin](https://github.com/OneBusAway/onebusaway-gtfs-realtime-munin-plugin) - Provides a [Munin](http://munin-monitoring.org/) plugin for logging information about a GTFS-realtime feed.
- [GTFS-realtime Nagio Plugin](https://github.com/OneBusAway/onebusaway-gtfs-realtime-nagios-plugin) - Provides a [Nagios](http://www.nagios.org/) plugin for monitoring a GTFS-realtime feed

### SIRI

- [SIRI API](https://github.com/OneBusAway/onebusaway/wiki/SIRI-Resources) - Java classes generated from the v1.0 and v1.3 [SIRI](http://user47094.vs.easily.co.uk/siri/) schemas.
- [SIRI 2.0 API] (https://github.com/laidig/siri-20-java) - Java classes generated from the v2.0 [SIRI](http://user47094.vs.easily.co.uk/siri/) schemas.
- [SIRI to GTFS-realtime](https://github.com/OneBusAway/onebusaway-gtfs-realtime-from-siri-cli/wiki) - A Java-based command-line utility to convert from the [SIRI format](http://user47094.vs.easily.co.uk/siri/) to GTFS-realtime.
- [SIRI 2.0 Autodoc](https://laidig.github.io/siri-20-java/doc/) - Automatically generated documentation from the (incredibly well) annotated SIRI 2.0 Schema Definition. 
- [King County Metro Legacy AVL to SIRI](https://github.com/bdferris/onebusaway-king-county-metro/tree/master/onebusaway-king-county-metro-legacy-avl-to-siri) - Java-based tool to convert [King County Metro's](http://metro.kingcounty.gov/) Legacy AVL format to GTFS-realtime.

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, Luqmaan Dawoodjee has waived all copyright and related or neighboring rights to this work.
