# OSM-Philippines AI assisted road mapping project

*Draft concept note for launching AI-Assisted mapping in the Philippines, final copy posted in [OSM Wiki](https://wiki.openstreetmap.org/wiki/Philippines/Tabang-AI) and talk-ph list.*

### Overview

Many advocates from the community of OpenStreetMap (OSM) users in the Philippines agree that OSM data coverage could be anywhere from very good to nil, depending on the geographic area, and the number of active local contributors. The community is seeking to define a baseline standard that is *good enough* for critical emergency and humanitarian response -- road network connectivity, essential facilities for emergency response and critical care, government offices, settlements, evacuation and assembly points -- and relegate detailed mapping to a suceeding phase, when local communities of contributors and users has been established.

This project intends to improve road data coverage for the Philippines through Facebook's (FB) mapwith.ai initiative. In the coming months, mapping projects will be initiated with collaborating local organizations/groups to use mapwith.ai data and tools in key geographies.  Throughout the duration of a mapping project, data added to OSM will be evaluated using a community defined data quality guidelines.

#### Context

The OSM community in the Philippines (OSM-PH) requested assistance from FB to provide artificial intelligence (AI) derived road detection for the country through the [mapwith.ai](https://mapwith.ai/) as a HOTOSM mapathon theme during the [Pista ng Mapa 2019 conference in Dumaguete](https://ti.to/pistangmapa/2019/). Based on the initial feedback from the workshop, it was demonstrated that the detections and workflow using a tasking manager and RapiD, substantially improved the speed and quality of mapping by new contributors to OpenStreetMap, and was also found helpful in guiding mappers with previous mapping experience to visualize where the detected roads are. Experienced mappers were also available during the mapathon, to provide mentoring and coaching support to new contributors.

This document is for the coordination of AI-assisted road mapping in the Philippines through FB's mapwith.ai initiative.

This project will be implemented in several phases to ensure that the data added to OSM conforms to the defined quality standards outlined by the local community.

![Screen Shot 2019-07-30 at 12 46 19](https://user-images.githubusercontent.com/353700/62353783-eba82600-b4fa-11e9-8260-929ce4c3e522.png)
_Sample detections (magenta) shown in RapiD in a rural village in Zambales, Philippines._


### Next steps

- [ ] Announce the initiative to talk-ph list for wider community discussion and inputs. 
- [ ] Develop a tasking manager prioritization framework using FB's High Resolution Settlement Layer (see [prior art](https://www.openstreetmap.org/user/maning/diary/371456)) to identify areas to map missing roads. [name=Maning Sambale]
- [ ] Develop a validation framework and quality metrics based on PH Road tagging guidelines.
- [ ] Beta test on a small area to gather feedback on prioritization and validation.
    - [ ] Launch a project to 1 city/province that will be lead by a local organization, with interest in utilizing the data.
    - [ ] Once ^^ is successful, start rolling out to other geographies.

### Collaborating groups

* OSM-PH - [Maning Sambale](https://www.openstreetmap.org/user/maning); [Eugene Alvin Villar](https://www.openstreetmap.org/user/seav)
* MapAm💜re Initiative/CWTS++ - [Erwin Olario](https://www.openstreetmap.org/user/GOwin)
* Humanitarian OSM Team - [Adityo](https://www.openstreetmap.org/user/Adityo); [harrymahar](https://www.openstreetmap.org/user/harrymahar) 
* Facebook

### FAQ

1. **What is Facebook's AI road data?**  Using artifical intelligence (AI), Facebook created models to extract road geometries from high resolution satellite imagery. The detections are then compared to existing OpenStreetMap road data. Detections that do not exist in OpenStreetMap are added into RapiD for human review and uploading to OpenStreetMap.  See details [here](https://ai.facebook.com/blog/mapping-roads-through-deep-learning-and-weakly-supervised-training).

2. **Will this collaboration involve mapping by the FB Maps team?** _No_, all mapping projects will be done by the local mapping community.  FB will only provide the detection and tools needed via the custom tasking manager and RapiD.

3. **Where do I contribute?** All mapping projects will be available at https://tasks-assisted.hotosm.org/.  New projects will be available soon and will be announced at the talk-ph mailing list.

4. **I have a team who want to map X place, can you setup a tasking project?** Sure! Please contact osm.pilipinas+aimappingrequest@gmail.com or via [github ticket](https://github.com/OSMPH/Tabang-AI/issues/new).

5. **I am a local mapper and I want to use RapiD to improve my mapping patch, do I need permission to use the tool?** _No_, if you are an individual, you can go ahead and use RapiD editor by itself. 

## See also

* [About OpenStreetMap Philippines](https://wiki.openstreetmap.org/wiki/Philippines)
* [Mapping roads through deep learning and weakly supervised training](https://ai.facebook.com/blog/mapping-roads-through-deep-learning-and-weakly-supervised-training)
* [General Questions about Map With AI](https://github.com/facebookmicrosites/Open-Mapping-At-Facebook/wiki/FAQ)
* [RapiD - an enhanced version of iD for mapping with AI](https://github.com/facebookincubator/RapiD)
