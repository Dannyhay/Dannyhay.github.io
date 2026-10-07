---
layout: page
title: "Research & Projects"
permalink: /Research/
---

My research asks a deceptively simple question: **which way does the arrow point?** When soil moisture and air temperature co-vary, when vegetation greens as the atmosphere dries, when a drought turns into a heatwave — what is driving what, how strongly, and does the answer change with the state of the system or with a warming climate? Answering it requires three things that run through everything I do: causal methods that work on observed, non-stationary climate time series; reliable observations of the land surface; and models that can be constrained by those observations.

<ul class="tags">
  <li>Liang–Kleeman information flow</li>
  <li>Time-varying causality</li>
  <li>Soil moisture–temperature coupling</li>
  <li>Compound dry–hot extremes</li>
  <li>Passive microwave remote sensing</li>
  <li>CLM–DART data assimilation</li>
  <li>CMIP6</li>
  <li>Causally-informed machine learning</li>
</ul>

<div class="theme">
<h3>1 · Causal inference for land–atmosphere interactions</h3>
<p>The land surface and the atmosphere are coupled through moisture and energy fluxes, but correlation-based coupling metrics cannot say which component is driving. I develop and apply <strong>information-theoretic causal methods</strong> — in particular the Liang–Kleeman information flow (LKIF), a rigorously derived measure of the rate at which one variable's evolution transfers uncertainty to another. My early work introduced a <em>time-varying</em> LKIF formalism for non-stationary climate systems, later extended to a <em>multivariate</em> setting in which time-dependent causal structures can be estimated among many interacting variables. Current work benchmarks the conditioning strategies used in LKIF, and brings causal importance into the training of physics-informed machine-learning models.</p>
<ul class="pubs">
  <li><span class="me">Hagan, D. F. T.</span>, Wang, G., Liang, X. S. &amp; Dolman, H. A. J. (2019). A time-varying causality formalism based on the Liang–Kleeman information flow for analyzing directed interactions in nonstationary climate systems. <em>Journal of Climate</em>, 32(16). <a href="https://doi.org/10.1175/JCLI-D-18-0881.1">doi:10.1175/JCLI-D-18-0881.1</a></li>
  <li><span class="me">Hagan, D. F. T.</span> et al. (2024). Estimating time-dependent structures in a multivariate causality for land–atmosphere interactions. <em>Journal of Climate</em>.</li>
  <li><span class="me">Hagan, D. F. T.</span>, Mortier, T., Decancq, C. &amp; Miralles, D. G. (2026). Causal importance for physics-informed machine learning. <em>Proceedings of Machine Learning Research</em> 323 (CLeaR 2026), 627–655.</li>
  <li>Benchmarking conditioners in Liang–Kleeman information flow: application to land–atmosphere interactions (2026, preprint).</li>
</ul>
</div>

<div class="theme">
<h3>2 · Soil moisture–temperature coupling and compound dry–hot extremes</h3>
<p>Soil-moisture deficits amplify heat, and heat deepens drought: this two-way coupling is at the heart of compound dry–hot extremes. Using causal metrics across observations, reanalyses and CMIP6 projections, I study how the strength, direction and even the sign of soil moisture–temperature coupling vary across regions and change under warming, and how the land surface modulates temperature trends and the carbon cycle. Within the ERC project <strong>HEAT</strong> and the FWO project <strong>CausalHeat</strong> this work targets the climatic drivers of human heat stress and the causal dynamics of dry and humid hot extremes, including a new daily <em>Standardized Soil Moisture–Temperature Compound Index</em> (SSTCI) and a global event catalogue of compound dry–hot extremes.</p>
<ul class="pubs">
  <li><span class="me">Hagan, D. F. T.</span>, Wang, G., Kennedy-Asser, A. T. et al. (2026). Divergent regional responses of soil moisture–air temperature coupling under future climate scenarios. <em>Nature Communications</em>, 17, 7311. <a href="https://doi.org/10.1038/s41467-026-74040-w">doi:10.1038/s41467-026-74040-w</a></li>
  <li>A daily soil moisture–temperature compound index for characterising dry–hot extremes (2026). <em>International Journal of Climatology</em>.</li>
  <li>Qiao, Y., Wang, G., <span class="me">Hagan, D. F. T.</span> et al. (2024). Contrasting sensitivity of air temperature trends to surface soil temperature trends between climate models and reanalyses. <em>npj Climate and Atmospheric Science</em>, 7.</li>
  <li><span class="me">Hagan, D. F. T.</span>, Dolman, H. A. J., Wang, G. et al. (2022). Contrasting ecosystem constraints on the seasonal terrestrial CO<sub>2</sub> and mean surface air temperature causality projections by the end of the 21st century. <em>Environmental Research Letters</em>. <a href="https://doi.org/10.1088/1748-9326/aca551">doi:10.1088/1748-9326/aca551</a></li>
  <li>Zou, X., Wang, G., <span class="me">Hagan, D. F. T.</span> et al. (2023). Precipitation sensitivity to soil moisture changes in multiple global climate models. <em>Atmosphere</em>, 14, 1531. <a href="https://doi.org/10.3390/atmos14101531">doi:10.3390/atmos14101531</a></li>
</ul>
</div>

<div class="theme">
<h3>3 · Vegetation–climate causality</h3>
<p>Vegetation sits in the middle of the land–atmosphere system: it responds to soil moisture and atmospheric dryness, and feeds back on both through transpiration and surface energy partitioning. With students and collaborators I use causal and multi-model approaches to ask how the vegetation response to soil moisture and vapour-pressure deficit is changing, how greening and transpiration are coupled in models versus observations, and how urban land-cover change alters the surface energy balance and heat-island intensity.</p>
<ul class="pubs">
  <li>Zhou, F., <span class="me">Hagan, D. F. T.</span>, Wang, G. et al. (2026). Declining vegetation response to soil moisture and vapor pressure deficit in Inner Mongolian grasslands. <em>Journal of Climate</em>, 39, 4617–4634. <a href="https://doi.org/10.1175/JCLI-D-25-0597.1">doi:10.1175/JCLI-D-25-0597.1</a></li>
  <li>Model–observation discrepancies in the coupling of vegetation greening and transpiration under rising vapor pressure deficit (2026). <em>Water Resources Research</em>.</li>
  <li>Observed declining strength of vegetation–atmosphere coupling (2026). <em>Agricultural and Forest Meteorology</em>.</li>
  <li>Shao, Y., <span class="me">Hagan, D. F. T.</span>, Li, S., Zhou, F., Zou, X. &amp; Cabral, P. (2024). The many shades of the vegetation–climate causality: a multimodel causal appreciation. <em>Forests</em>, 15, 1430. <a href="https://doi.org/10.3390/f15081430">doi:10.3390/f15081430</a></li>
  <li>Yeboah, E., <span class="me">Hagan, D. F. T.</span>, Wang, G. et al. (2026). Understanding the causal influence of energy balance components on urban heat islands in a mid-latitude city — Chongqing, China. <em>Urban Climate</em>, 65, 102735. <a href="https://doi.org/10.1016/j.uclim.2025.102735">doi:10.1016/j.uclim.2025.102735</a></li>
</ul>
</div>

<div class="theme">
<h3>4 · Satellite soil moisture and land surface temperature from passive microwaves</h3>
<p>Good causal inference needs good observations. Since 2015 I have led the longest-running effort to retrieve and improve surface soil moisture from China's FengYun-3 passive-microwave sensors, developing improvement schemes for the Land Parameter Retrieval Model (LPRM) that account for open-water fraction and improved scattering albedo, improving a land-surface-temperature retrieval algorithm, and merging multi-sensor records with an emphasis on preserving temporal correlation. The result is a seamless, finer-resolution soil-moisture record from the FengYun-3 series published in <em>Scientific Data</em>.</p>
<figure>
  <a href="{{ '/figure/fy3_timeline.jpg' | relative_url }}"><img src="{{ '/figure/fy3_timeline.jpg' | relative_url }}" alt="Timeline of twelve years of FengYun-3 passive-microwave LPRM soil-moisture research, 2014–2025, from FY-3B to FY-3D"></a>
  <figcaption>Twelve years of FengYun-3 passive-microwave LPRM soil moisture — the longest study of soil moisture from China's passive-microwave observations, from the first FY-3B evaluation (2014) to the seamless FY-3B/C/D record in <em>Scientific Data</em> (2025).</figcaption>
</figure>
<ul class="pubs">
  <li><span class="me">Hagan, D. F. T.</span>, Kim, S., Wang, G. et al. (2025). Seamless finer-resolution soil moisture from the synergistic merging of the FengYun-3 satellite series. <em>Scientific Data</em>, 12, 983. <a href="https://doi.org/10.1038/s41597-025-05263-7">doi:10.1038/s41597-025-05263-7</a></li>
  <li>Wang, G., Ma, X., <span class="me">Hagan, D. F. T.</span> et al. (2022). Towards consistent soil moisture records from China's FengYun-3 microwave observations. <em>Remote Sensing</em>, 14, 1225. <a href="https://doi.org/10.3390/rs14051225">doi:10.3390/rs14051225</a></li>
  <li><span class="me">Hagan, D. F. T.</span>, Wang, G., Kim, S. et al. (2020). Maximizing temporal correlations in long-term global satellite soil moisture data-merging. <em>Remote Sensing</em>, 12, 2164. <a href="https://www.mdpi.com/2072-4292/12/13/2164">mdpi.com</a></li>
  <li><span class="me">Hagan, D. F. T.</span>, Wang, G., Parinussa, R. &amp; Shi, S. (2019). Inter-comparing and improving land surface temperature estimates from passive microwaves over the Jiangsu province of the People's Republic of China. <em>International Journal of Remote Sensing</em>, 40(14), 5563–5584. <a href="https://doi.org/10.1080/01431161.2019.1580790">doi:10.1080/01431161.2019.1580790</a></li>
  <li>Wang, G., <span class="me">Hagan, D. F. T.</span>, Lou, D. &amp; Chen, T. (2016). Evaluation of soil moisture derived from FY3B microwave brightness temperature over the Tibetan Plateau. <em>Remote Sensing Letters</em>, 7(9), 817–826. <a href="https://doi.org/10.1080/2150704X.2016.1192303">doi:10.1080/2150704X.2016.1192303</a></li>
</ul>
</div>

<div class="theme">
<h3>5 · Land data assimilation</h3>
<p>Observations and models are strongest together. As a visiting scholar and now external collaborator of NCAR's Data Assimilation Research Section, I work with the Data Assimilation Research Testbed (DART) coupled to the Community Land Model (CLM) to assimilate satellite soil moisture, improve the representation of land-surface processes, and support drought monitoring and forecasting — including applications over India and the contiguous United States.</p>
<ul class="pubs">
  <li>Heyvaert, Z., Bechtold, M., Dorigo, W., Mortelmans, J., <span class="me">Hagan, D. F. T.</span>, Santanello, J. &amp; De Lannoy, G. (2025). Land data assimilation of satellite-based surface soil moisture: impact on atmospheric simulations over the contiguous United States. <em>Quarterly Journal of the Royal Meteorological Society</em>, 152(775).</li>
  <li>Improving the representation of land surface processes using the Data Assimilation Research Testbed (DART) (2025, conference contribution).</li>
  <li>Advancing drought monitoring in India through land data assimilation with CLM5-DART (2025, conference contribution).</li>
  <li><span class="me">Hagan, D. F. T.</span>, Parinussa, R., Wang, G. &amp; Draper, C. (2019). An evaluation of soil moisture anomalies from global model-based datasets over the People's Republic of China. <em>Water</em>, 12(1), 117. <a href="https://doi.org/10.3390/w12010117">doi:10.3390/w12010117</a></li>
</ul>
</div>

<div class="theme">
<h3>6 · Evapotranspiration, drought and water security</h3>
<p>Much of my applied work concerns droughts and water availability in Africa and Asia: long-term and future changes in evapotranspiration and drought over China and continental Africa, the hydro-climatic drivers of crop production in equatorial Africa, heatwave–wildfire relationships over Africa, and the climatic drivers of heat extremes over the Sahel. I led the Belt-and-Road project <em>Tackling sustainable water resources and food security constraints over the China–Pakistan Economic Corridor in a warming world</em>, and I co-developed a harmonised global land-evaporation dataset.</p>
<ul class="pubs">
  <li>Lu, J., Wang, G., Chen, T., Li, S., <span class="me">Hagan, D. F. T.</span> et al. (2021). A harmonized global land evaporation dataset from model-based products covering 1980–2017. <em>Earth System Science Data</em>, 13, 5879–5898.</li>
  <li>Li, S., Wang, G., Sun, S., <span class="me">Hagan, D. F. T.</span> et al. (2021). Long-term changes in evapotranspiration over China and attribution to climatic drivers during 1980–2010. <em>Journal of Hydrology</em>, 595, 126037.</li>
  <li>Nooni, I. K., <span class="me">Hagan, D. F. T.</span> et al. (2022). Projections of drought characteristics based on the CNRM-CM6 model over Africa. <em>Agriculture</em>, 12, 495. <a href="https://doi.org/10.3390/agriculture12040495">doi:10.3390/agriculture12040495</a></li>
  <li>Nooni, I. K., Ogou, F. K., <span class="me">Hagan, D. F. T.</span> et al. (2024). The relationship between changes in hydro-climate factors and maize crop production in the equatorial African region from 1980 to 2021. <em>Atmosphere</em>, 15, 542. <a href="https://doi.org/10.3390/atmos15050542">doi:10.3390/atmos15050542</a></li>
  <li>Low built-up density emerges as a key driver of heat extremes over the Sahel (2026).</li>
</ul>
</div>

## Projects

<table class="projects">
  <tr><th>Project</th><th>Funder</th><th>Period</th><th>Role</th></tr>
  <tr><td><strong>HEAT</strong> — Hybrid dry–hot Extremes prediction and AdapTation</td><td>European Research Council</td><td>2023–</td><td>Senior research scientist, H-CEL</td></tr>
  <tr><td><strong>CausalHeat</strong> — Mapping the causal dynamics of dry and humid hot extremes (Belgium–China)</td><td>Research Foundation – Flanders (FWO)</td><td>2025–2027</td><td>Co-PI</td></tr>
  <tr><td><strong>Causal Inference for Geoscience</strong></td><td>Government of Singapore</td><td>newly approved</td><td>Co-PI</td></tr>
  <tr><td><strong>IcyAlert</strong> — Intelligent Climate Early Warning Alert for Arctic Ice-Free Summers (<a href="https://icyalert.github.io">icyalert.github.io</a>)</td><td>Novo Nordisk Foundation</td><td>2025–2031</td><td>Advisor</td></tr>
  <tr><td>Tackling sustainable water resources and food security constraints over the China–Pakistan Economic Corridor in a warming world</td><td>Belt and Road Initiative (China)</td><td>completed</td><td>PI (applied for, received and managed)</td></tr>
</table>

Two patents were granted for algorithms I developed for causality analysis and extreme-climate evaluation.
