---
name: FM1.1 Deepwater coastal inlets
biome: FM1. Semi-confined transitional waters biome
realm: Freshwater, Marine
code: FM1.1
biomecode: FM1
contributors: DA Keith, EJ Gregr, A Lindgaard, TS Bianchi
mapcontributors: JR Ferrer-Paris, DA Keith
version: v2.1 (2022-04-06)
---
# Ecosystem properties

Deepwater coastal inlets (e.g. fjords, sea lochs) are semi-confined aquatic systems with many features of open oceans. Strong influences from adjacent freshwater and terrestrial systems produce striking environmental and biotic gradients. Autochthonous energy sources are dominant, but allochthonous sources (e.g. glacial ice discharge, freshwater streams, and seasonal permafrost meltwater) may contribute 10% or more of particulate organic matter. Phytoplankton, notably diatoms, contribute most of the primary production, along with biofilms and macroalgae in the epibenthic layer. Seasonal variation in inflow, temperatures, ice cover, and insolation drives pulses of in situ and imported productivity that generate blooms in diatoms, consumed in turn by jellyfish, micronekton, a hierarchy of fish predators, and marine mammals. Fish are limited by food, density-dependent predation, and cannibalism. As well as driving pelagic trophic networks, seasonal pulses of diatoms shape biogeochemical cycles and the distribution and biomass of benthic biota when they senesce and sink to the bottom, escaping herbivores, which are limited by predators. The vertical flux of diatoms, macrophytes, and terrestrial detritus sustains a diversity and abundance of benthic filter-feeders (e.g. maldanids and oweniids). Environmental and biotic heterogeneity underpins functional and compositional contrasts between inlets and strong gradients within them. Zooplankton, fish, and jellies distribute in response to resource heterogeneity, environmental cues, and interactions with other organisms. Deep inlets sequester more organic carbon into sediments than other estuaries (FM1.2, FM1.3) because steep slopes enable efficient influx of terrestrial carbon and low-oxygen bottom waters abate decay rates. Inlets with warmer water have more complex trophic webs, stronger pelagic-benthic coupling, and utilise a greater fraction of organic carbon, sequestering it in sea-floor sediments at a slower rate than those with cold water.

# Ecological Drivers

Deepwater coastal systems may exceed 300 km in length and 2 km in depth. Almost all have glacial origins and many are fed by active glaciers. The ocean interface at the mouth of the inlets, strongly influenced by regional currents, interacts with large seasonal inputs of freshwater to the inner inlet and wind-driven advection, to produce strong and dynamic spatial gradients in nutrients, salinity and organic carbon. Advection is critical to productivity and carrying capacity of the system. Advection drives water movement in the upper and lower layers of the water column in different directions, linking inlet waters with coastal water masses. Coastal currents also mediate upwelling and downwelling depending on the direction of flow. However, submerged glacial moraines or sills at the inlet mouth may limit marine mixing, which can be limited to seasonal episodes in spring and autumn. Depth gradients in light typically extend beyond the photic zone and are exacerbated at high latitudes by seasonal variation in insolation and surface ice. Vertical fluxes also create strong depth gradients in nutrients, oxygen, dissolved organic carbon, salinity, and temperature.

# Diagramatic assembly model

{% include DAM.html %}

# Distribution

Historically or currently glaciated coastlines at polar and cool-temperate latitudes.

{% capture map_det %}
Known locations of fjords were selected from a global geographical gazetteer (GeoNames, 2020) and the composite gazetteer of Antarctica (SCAR, 1992-2020). We further selected related coastal areas from a global coastal typology (Type IV in Dürr et al., 2011) and the adjacent marine shelves to 2000 metre depth (Becker et al., 2009). A composite map was created at 30 arc seconds spatial resolution in geographic projection, occurrences were then aggregated to half degree spatial resolution and reclassified as major occurrences (cells with at least one known occurrence) and minor occurrences (cells with > 5% occurrence of coastal/marine shelf areas). Minor occurrences were clipped to a 50km buffer along the coast to remove inland and oceanic areas.
{% endcapture %}
{% include MAP.html %}

## References
### Main References
* Bianchi TS, Arndt S, Austin WEN, Benn DI, Bertrand S, Cui X, Faust JC, Koziorowska-Makuch K, Moy CM, Savage C, Smeaton C, Smith RW, Syvitski J (2020) Fjords as Aquatic Critical Zones (ACZs). Earth-Science Reviews 203, 103145.
* Salvanes AGV (2001) Review of ecosystem models of fjords; new insights of relevance to fisheries management. Sarsia 86:441-463.
* Zaborska A, Włodarska-Kowalczuk M, Legeżyńska J et al. (2018) Sedimentary organic matter sources, benthic consumption and burial in west Spitsbergen fjords – Signs of maturing of Arctic fjordic systems? Journal of Marine Systems 180: 112–123.
### Map References
* Becker JJ, Sandwell DT, Smith WHF, Braud J, Binder B, Depner J, Fabre D, Factor J, Ingalls S, Kim S-H, Ladner R, Marks K, Nelson S, Pharaoh A, Trimmer R, Von Rosenberg J, Wallace G, Weatherall P (2009) *Global Bathymetry and Elevation Data at 30 Arc Seconds Resolution: SRTM30_PLUS*, **Marine Geodesy** 32: 355-371. DOI:[10.1080/01490410903297766](https://doi.org/10.1080/01490410903297766)
* Dürr, H. H., G. G. Laruelle, C. M. van Kempen, C. P. Slomp, M. Meybeck and H. Middelkoop (2011) *Worldwide Typology of Nearshore Coastal Systems: Defining the Estuarine Filter of River Inputs to the Oceans*. **Estuaries and Coasts**, 34(3), 441-458, doi:[10.1007/s12237-011-9381-y](http://dx.doi.org/10.1007/s12237-011-9381-y)
* GeoNames (2020) The GeoNames geographical database. https://www.geonames.org [Accessed in Feb 2020]
* Secretariat SCAR (1992, updated 2020). *Composite Gazetteer of Antarctica*, **Scientific Committee on Antarctic Research**. [GCMD Metadata](http://gcmd.nasa.gov/records/SCAR_Gazetteer.html)
