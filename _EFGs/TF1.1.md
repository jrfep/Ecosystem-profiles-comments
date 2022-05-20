---
name: TF1.1 Tropical flooded forests and peat forests
biome: TF1. Palustrine wetlands biome
realm: Terrestrial, Freshwater
code: TF1.1
biomecode: TF1
contributors: DA Keith, RT Kingsford, R Mac Nally, KM Rodriguez-Clark, A Etter
version: v2.1 (2022-04-06)
mapcode: TF1.1.IM.alt_v4.0
---
# Ecosystem properties

Closed-canopy forests in tropical swamps and riparian zones have high biomass and LAI, with unseasonal growth and reproductive phenology. The canopy foliage is evergreen, varying in size from mesophyll to notophyll with moderate SLA. Productivity differs markedly between high-nutrient ‘white water’ riparian systems and low-nutrient ‘black water’ systems. In the latter, most of the nutrient capital is sequestered in plant biomass, litter, or peat, whereas in white water systems, soil nutrients are replenished continually by fluvial subsidies. Some trees have specialised traits conferring tolerance to low-oxygen substrates, such as surface root mats, pneumatophores, and stilt roots. Palms (sometimes in pure stands), hydrophytes, pitcher plants, epiphytic mosses, and ferns may be abundant, but lianas and grasses are rare or absent. The recent origin of these forests has allowed limited time for evolutionary divergence from nearby lowland rainforests (T1.1), but strong filtering by saturated soils has resulted in low diversity and some endemism. The biota is spatially structured by local hydrological gradients. Riparian galleries of floodplain forests also occur within savanna matrices. Trophic networks are complex but with less diverse representation of vertebrate consumers and predators than T1.1, although avian frugivores, primates, amphibians, macro-invertebrates, and crocodilian predators are prominent. Plant propagules are dispersed mostly by surface water or vertebrates. Seed dormancy and seedbanks are rare. Gap-phase dynamics are driven by individual treefall, storm events, or floods in riparian forests, but many plants exhibit leaf-form plasticity and can recruit in the shade.

# Ecological Drivers

High rainfall, overbank flows or high water tables maintain an abundant water supply. Continual soil profile saturation leads to anaerobic black water conditions and peat accumulation. In contrast, white water riparian zones undergo frequent fluvial disturbance and drain rapidly. Peat forests often develop behind lake shore vegetation or mangroves, which block lateral drainage. Black water peatlands may become domed, ombrogenous (i.e. rain-dependent), highly acidic, and nutrient-poor, with peat accumulating to depths of 20 m. In contrast, white water riparian forests are less permanently inundated and floods continually replenish nutrients, disturb vegetation, and rework sediments. Hummock-hollow micro-topography is characteristic of all forested wetlands and contributes to niche diversity. Light may be limited by dense tree canopies. There is low diurnal, intra- and inter-annual variability in rainfall and temperature, with the latter rarely <10°C, which promotes microbial activity when oxygen is available.

# Diagramatic assembly model

{% include DAM.html %}

# Distribution

Flat equatorial lowlands of Southeast Asia, South America, and Central and West Africa, notably in Borneo and the Amazonian lowlands.

{% assign map = site.data.mapinfo[page.mapcode] %}
{% assign map_det = map.description %}
{% include MAP.html %}

## References
### Main References
* Page SE, Rieley JO, Wüst R (2014) Lowland tropical peatlands of Southeast Asia. In: Peatlands: Evolution and records of environmental and climate changes (Eds. IP Martini, Martínez A Cortizas, W Chesworth), pp145-172. Elsevier, Amsterdam. 
### Map References
{% for ref in map.contributors %}
* {{ref}}
{% endfor %}
