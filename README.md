# Acrylamide exposure from diet

In this project we calculate the individual exposure of acrylamide from diet and compare this estimate with an exposure estimate based on measured acrylamide hemoglobin adducts in the blood of the same individuals. We use data from the EuroMix biomonitoring study in the project. The results will be published in the paper "Dietary intake of acrylamide in the Norwegian EuroMix biomonitoring study: comparing probabilistic dietary estimates with Hb adduct measurements" by Efstathios Vryonidis, Margareta Törnqvist, Oddvar Myhre, Hubert Dirven, Trine Husøy.

Acrylamide is a process induced chemical, that is formed by heating of foods rich in carbohydrates such as french fries, potato crisps, and bread. Acrylamide induce tumours in mice and rats and is suspected to also act as an carcinogen in humans. The metabolism of acrylamide to the genotoxic metabolite glycidamide is considered to be crucial for the observed carcinogenicity of acrylamide, and both acrylamide and glycidamide reach with proteins (for example hemoglobine) and create protein adducts. In addition acrylamide is a neurotoxicant in humans, shown in occupational exposure studies. It is therefore crucial to have a good estimate of human exposure to evaluate the human risk.

The EuroMix study is a small (n=144) bionomitoring study performed as a part of the EU funded scientific project “European Test and Risk Assessment Strategies for Mixtures (EuroMix)”.  Participants recorded and weighed their food consumption (weighed food record) for a 24h period on two non-consecutive days (2-3 weeks between) in a diary. Blood was collected at the end of each 24-hour period.

Probabilistic exposure assessment of acrylamide was estimated from the food consumption reported in the EuroMix diaries and acrylamide concentrations in foods reported by the food Food Authorities in Norway. Acrylamide hemoglobin adducts were measured in the blood from the EuroMix participants and these measurements were used to estimate human exposure (not described further here). The two exposure estimates were compared.

The probabilistic exposure assessment were performed in R version 3.6.2, and the code is included in this repository. Due to ethical reasons the individual data from the EuroMix study cannot be openly shared. Therefore dummy data was created through randomly and independent selection of each variable from the EuroMix data. These dummy data is included in the repository for testing purposes. 
