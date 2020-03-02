### Feature Catalogue

Contents:
* [Farm Features](#Farm-Features)
* [Feature Hierarchy](#Feature-Hierarchy)

This section of the document is a Feature Catalogue aligned to terms described in [ISO 19110](https://www.iso.org/obp/ui/#iso:std:iso:19110:ed-1:v1:en). Use of features for agricultural purposes overlaps with other uses of the same feature types, and as a result many of the features listed here are defined in other standards. 

Overlaps are resolved as follows:

* The primary standard for any feature types in another domain is referenced beside that feature type; and

* The [Feature Attributes Data Dictionary](docs/FFADS_Feature-Attributes-Data-Dictionary.md) describes attributes for these features that are most relevant to the NZ primary sector, but does not reproduce all attributes from a referenced Standard. The reader is to use the referenced Standard as the definitive source to ascertain relevant attributes.

#### Farm Features

Feature Type | Definition | Synonyms | Feature Catalogue/Package
:----------- | :--------- | :------- | :------------------------
[Cadastral](docs/FFADS_Definitions-and-Abbreviations.md#Definitions-and-Abbreviations) Parcel | Area defined by [cadastral](docs/FFADS_Definitions-and-Abbreviations.md#Definitions-and-Abbreviations) registers or equivalent. In NZ, the cadastral parcel encompasses the entire area of a farm property. | Land Parcel, Land Title, Property title	| [INSPIRE D2.8.I.6 Data Specification on Cadastral Parcels – Technical Guidelines](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_CP_v3.1.pdf)
[Cadastral](docs/FFADS_Definitions-and-Abbreviations.md#Definitions-and-Abbreviations) Boundary | Part of the outline of a [cadastral](docs/FFADS_Definitions-and-Abbreviations.md#Definitions-and-Abbreviations) parcel. One [cadastral](docs/FFADS_Definitions-and-Abbreviations.md#Definitions-and-Abbreviations) boundary may be shared by two neighbouring [cadastral](docs/FFADS_Definitions-and-Abbreviations.md#Definitions-and-Abbreviations) parcels. | Real property boundary | [INSPIRE D2.8.I.6 Data Specification on Cadastral Parcels – Technical Guidelines](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_CP_v3.1.pdf)
Holding | The whole area and all infrastructures included on it, under the control of an operator to perform agricultural or aquaculture activities. It must be composed of one or more Sites. It could be considered as the synthetic geographical representation of a unique operational, economical or legal body. | Farm Unit, Agribusiness Unit, Farm Entity | [D2.8.III.9 INSPIRE Data Specification on Agricultural and Aquaculture Facilities – Technical Guidelines.](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_AF_v3.0.pdf) Farm Entity: [Farm and Model Data Standard](http://www.farmdatastandards.org.nz/wp-content/uploads/2016/03/DINDS-Farm-Model-Data-Discussion-2015-01-09.pdf)
Site | Belonging to a holding, it is the geographical representation of land that constitutes a management unit. It includes all infrastructure, equipment and materials. | Farm Block, Management Block, Land Management Unit ([LMU]Land Management Unit) | [D2.8.III.9 INSPIRE Data Specification on Agricultural and Aquaculture Facilities –Technical Guidelines](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_AF_v3.0.pdf) Management Block: [Farm and Model Data Standard](http://www.farmdatastandards.org.nz/wp-content/uploads/2016/03/DINDS-Farm-Model-Data-Discussion-2015-01-09.pdf)
Plot | Independent portion of land or water surface (clearly delimited e.g. by fences, markers etc) including (or matching) the limits of a Site, that is the support for a specific use directly related to Agricultural activities. | | [D2.8.III.9 INSPIRE Data Specification on Agricultural and Aquaculture Facilities – Technical Guidelines.](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_AF_v3.0.pdf)
Field | Special case of a Plot or Site that is used to grow arable crops. | | 
Paddock | Special case of a Plot or Site that is used to graze livestock. | |[Plot Special Case Attributes](docs/FFA_Feature-Attributes-Data-Dictionary.md#Plot-Special-Case-Attributes)
Wetland | A poorly drained or periodically flooded area where the soil is saturated with water, and vegetation is supported. | Swamp | [D2.8.I.8 Data Specification on Hydrography – Technical Guidelines](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_HY_v3.1.pdf)
Drainage Basin | Area having a common outlet for its surface runoff. | Sub-basin, catchment; catchment area; drainage area; river basin; watershed.	| [D2.8.I.8 Data Specification on Hydrography – Technical Guidelines](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_HY_v3.1.pdf)
Management, Restriction or Regulation Zone | Area managed, regulated or used for reporting at international, national, regional and local levels.
Extended to include information describing activities that are controlled to achieve specific environment objectives within the zone. | Management Zone, Regulation Zone, Restriction Zone | [D2.8.III.11 Data Specification on Area Management/Restriction/Regulation Zones and Reporting Units – Technical Guidelines](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_AM_v3.0.pdf)
Riparian Zone | Special case of a management restriction or regulation zone. The interface between land and a watercourse, designated for special protection, such as the Sustainable Dairy Water Accord ([SDWA](http://www.dairynz.co.nz/media/3286407/sustainable-dairying-water-accord-2015.pdf)). | | [Riparian Zone Attributes](docs/FFA_Feature-Attributes-Data-Dictionary.md#Riparian-Zone-Attributes)
Soil Body | Part of the soil cover that is delineated and that is homogeneous with regard to certain soil properties and/or spatial patterns. NB: This is synonymous with soil zones as defined in Farm and Model Data Standard. | Soil Type, Soil Zone | [D2.8.III.3 INSPIRE Data Specification on Soil – Technical Guidelines](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_SO_v3.0.pdf)<br> [ANZSoilML](http://anzsoil.org/doc/anzsoilml/html/2.0.0/) <br> Soil Zone: [Farm and Model Data Standard](http://www.farmdatastandards.org.nz/wp-content/uploads/2016/03/DINDS-Farm-Model-Data-Discussion-2015-01-09.pdf) 
Protected Site | An area designated or managed within a framework of international, Community and Member States' legislation to achieve specific conservation objectives. IN NZ, this could be used for [QEII](docs/FFADS_Definitions-and-Abbreviations.md#Definitions-and-Abbreviations) Conservation zones. | Cultural Site, Ecological Area, Archaeological Site | [D2.8.I.9 Data Specification on Protected Sites – Technical Guidelines](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_PS_v3.2.pdf) 
Land Cover Unit | The geometry of a Land Cover observation. More commonly used for regional and national planning purposes. | Forest, Pastures, Permanently Irrigated Land, etc | [D2.8.II.2 INSPIRE Data Specification on Land Cover – Technical Guidelines](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_LC_v3.0.pdf) 
Watercourse | A natural or man-made flowing watercourse or stream. | River, Stream | D2.8.I.8 Data Specification on Hydrography – Technical Guidelines
Crossing | A man-made object allowing the passage of water above or below an obstacle. | Bridge, Culvert | [D2.8.I.8 Data Specification on Hydrography – Technical Guidelines](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_HY_v3.1.pdf)
Dam or Weir	| A permanent barrier across a watercourse used to impound water or to control its flow. | Dam, Weir | [D2.8.I.8 Data Specification on Hydrography –  Technical Guidelines](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_HY_v3.1.pdf)
Waterway | A collection of water link sequences and or individual waterway and/or watercourse links that are characterized by one or more thematical identifiers and/or properties, which perform a navigable route within a water body (oceans, seas, rivers, lakes, channels or canals). | Canal, Navigable Waterway | INSPIRE [D2.8.I.7 Data Specification on Transport Networks – Technical Guidelines](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_TN_v3.2.pdf)
Utility Network | Collection of network elements that belong to a single type of utility network. | | [D2.8.III.6 INSPIRE Data Specification on Utility and Government Services – Technical Guidelines](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_US_v3.0.pdf)
Utility Link | A linear spatial object that describes the geometry and connectivity of a utility network between two points in the network, e.g. Cable, pipe, and ducts. | | [D2.8.III.6 INSPIRE Data Specification on Utility and Government Services – Technical Guidelines](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_US_v3.0.pdf) 
Utility Node Container | A point spatial object used for connectivity, and may also contain other spatial objects eg tower, manhole, pole | | [D2.8.III.6 INSPIRE Data Specification on Utility and Government Services – Technical Guidelines](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_US_v3.0.pdf)
Pipe | A utility link or link sequence for the conveyance of solids, liquids, chemicals or gases from one location to another. A pipe can also be used as an object to encase several cables (a bundle of cables) or other (smaller) pipes. | Pipeline | [D2.8.III.6 INSPIRE Data Specification on Utility and Government Services – Technical Guidelines](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_US_v3.0.pdf)
Cable | A utility link or link sequence used to convey electricity or data from one location to another. | | [D2.8.III.6 INSPIRE Data Specification on Utility and Government Services – Technical Guidelines](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_US_v3.0.pdf)
Duct | A utility link or link sequence used to protect and guide cable and pipes via an encasing construction | | [D2.8.III.6 INSPIRE Data Specification on Utility and Government Services – Technical Guidelines](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_US_v3.0.pdf) 
Tower | Simple tower object which may carry utility objects belonging to either single or multiple utility networks | | [D2.8.III.6 INSPIRE Data Specification on Utility and Government Services – Technical Guidelines](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_US_v3.0.pdf)
Manhole | Simple container object which may carry utility objects belonging to ether single or multiple utility networks. | | [D2.8.III.6 INSPIRE Data Specification on Utility and Government Services – Technical Guidelines](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_US_v3.0.pdf)
Pole | Simple pole (mast) object which may carry utility objects belonging to ether single or multiple utility networks. | | [D2.8.III.6 INSPIRE Data Specification on Utility and Government Services – Technical Guidelines](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_US_v3.0.pdf)
Cabinet | Simple cabinet object which may carry utility objects belonging to ether single or multiple utility networks.	| | [D2.8.III.6 INSPIRE Data Specification on Utility and Government Services – Technical Guidelines](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_US_v3.0.pdf)
Fence | A mesh, railing, hedge, or the like for preventing free access to an area. | Hedge, Railing | [Fence and Gate Attributes](docs/FFA_Feature-Attributes-Data-Dictionary.md#Fence-and-Gate-Attributes)
Gate | An opening in a fence or other enclosure, for the purpose of giving pedestrian or vehicular entry and exit, and capable of being closed with a barrier. | Grid | [Fence and Gate Attributes](docs/FFA_Feature-Attributes-Data-Dictionary.md#Fence-and-Gate-Attributes)
Road | A collection of road or track link sequences and/or individual road links that are characterized by one or more thematic identifiers and/or properties. | 	Track, Race | [INSPIRE D2.8.I.7 Data Specification on Transport Networks – Technical Guidelines](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_TN_v3.2.pdf)
Aerodrome Area | A defined area on land or water (including any buildings, installations and equipment) intended to be used either wholly or in part for the arrival, departure and surface movement of aircraft and/or helicopters. | Runway | [INSPIRE D2.8.I.7 Data Specification on Transport Networks – Technical Guidelines](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_TN_v3.2.pdf)
Agri Building | A construction to store agricultural commodities, harvested crops, keeping of animals or storing equipment. | Animal housing, Product storage, Equipment shed | [D2.8.III.9 INSPIRE Data Specification on Agricultural and Aquaculture Facilities – Technical Guidelines](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_AF_v3.0.pdf) <br> Additional structure attributes – Farm and model – [Section 5.8](http://www.farmdatastandards.org.nz/wp-content/uploads/2016/03/DINDS-Farm-Model-Data-Discussion-2015-01-09.pdf)
Installation | Stationary technical unit part of a facility where one or more Agricultural activities are carried out, and any other directly associated activities which have a technical connection with the activities carried out on that site.	| Dairy shed, Shearing sheds, offal pit, dump, quarry | [D2.8.III.9 INSPIRE Data Specification on Agricultural and Aquaculture Facilities – Technical Guidelines](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_AF_v3.0.pdf) <br> Additional structure attributes – Farm and model Data Standard – [Section 5.8](http://www.farmdatastandards.org.nz/wp-content/uploads/2016/03/DINDS-Farm-Model-Data-Discussion-2015-01-09.pdf)
Water Management Installation | The source of water used for activities of the Site. | Irrigator, Well, Water Supply | [D2.8.III.9 INSPIRE Data Specification on Agricultural and Aquaculture Facilities – Technical Guidelines](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_AF_v3.0.pdf) 
Contour Line | Linear spatial object composed of a set of adjoining locations characterized by having the same elevation property value. It describes, together with other contour lines present in the area, the local morphology of the Earth's surface | Contour | [D2.8.II.1 INSPIRE Data Specification on Elevation – Technical Guidelines](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_EL_v3.0.pdf) 
Spot Elevation | Class of spot elevation according to the LAS specification of the American Society for Photogrammetry and Remote Sensing (ASPRS). | Spot Height | [D2.8.II.1 INSPIRE Data Specification on Elevation – Technical Guidelines](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_EL_v3.0.pdf) 
Hazard Area | Discrete spatial objects representing a natural hazard namely geological, hydro-meteorological or biological. For additional attributes, refer to the Health and Safety Data Standard. | Hazard, Bluff | [D2.8.III.12 INSPIRE Data Specification on Natural Risk Zones – Technical Guidelines](http://inspire.ec.europa.eu/documents/Data_Specifications/INSPIRE_DataSpecification_NZ_v3.0.pdf)
Emergency Locations | Spatial objects representing an emergency location eg | Evacuation point | [Emergency Location Attributes](docs/FFA_Feature-Attributes-Data-Dictionary.md#Emergency-Location-Attributes)
 
#### Feature Hierarchy

The diagram below illustrates the hierarchy of each spatial feature as defined by NZ Farm Data Standards, beginning with the Holding as the broad definition of the total farm area. Each vertical level represents a sub-layer of the preceding feature.
 
![FeatureHeirarchy](FFADS_FeatureHeirarchy.png "Farm Features And Attributes Data Standards Feature Heirarchy")