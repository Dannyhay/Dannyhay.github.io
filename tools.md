---
layout: page
title: "Data & Tools"
permalink: /Tools/
---

Open datasets and methods from my research. Everything below is freely available; if you use a dataset, please cite the associated paper or data record.

<div class="dataset">
<h3>slimcol — a laptop-scale soil–vegetation–atmosphere column model <span class="badge badge-soon">Coming soon</span></h3>
<figure>
  <a href="{{ '/figure/slimcol_overview.jpg' | relative_url }}"><img src="{{ '/figure/slimcol_overview.jpg' | relative_url }}" alt="Schematic of the slimcol two-source column model: forcing, surface layer, tree and grass tiles with sunlit and shaded leaves, plant hydraulics, a three-store bucket hydrology and soil heat, observation operators and evaluation"></a>
  <figcaption>slimcol at a glance: two-source canopy and ground energy balances in tree and grass tiles, a three-store bucket with a deep reservoir, optional plant hydraulics and an optional mixed-layer atmosphere, evaluated against eddy-covariance towers.</figcaption>
</figure>
<p>slimcol is a Python column model built to make heat-wave mechanisms <em>testable</em>: every physical pathway can be switched on or off, so you can see directly what each one does to surface temperature and fluxes. It began as a port of the SLIM and SEMB simple land models and has grown into a two-source model (since 2022) with</p>
<ul>
  <li>separate energy balances for the canopy and the ground surface, with Monin–Obukhov surface-layer exchange;</li>
  <li>Farquhar–Medlyn leaf photosynthesis and stomatal conductance, with layered shortwave and longwave radiation;</li>
  <li>a three-store soil-water bucket with a deep reservoir, ten-layer soil heat and a water-supply feedback that turns latent heat the soil cannot supply into sensible heat;</li>
  <li>optional plant hydraulics, side-by-side tree and grass tiles, carbon fluxes, and an optional coupled mixed-layer atmosphere driven by ERA5.</li>
</ul>
<p>The core land model is in place and tested; plant hydraulics, tiles and the coupled atmosphere are still being evaluated. The code and a reference manual will be released here once the evaluation is complete.</p>
</div>

<div class="dataset">
<h3>Standardized Soil Moisture–Temperature Compound Index (SSTCI) and global CDHE event catalogue, 1961–2023</h3>
<p>Two linked products for global compound dry–hot extremes (CDHEs) over land at 0.1° resolution: a continuous <strong>daily severity index</strong>, built from soil-moisture memory and surface air temperature, and a ready-to-use <strong>event catalogue</strong> recording when and where each CDHE occurred, its duration and its severity. The method is described in the <em>International Journal of Climatology</em> (2026); the dataset and catalogue are described in <em>Earth System Science Data</em> (2026), where the paper was selected as a highlight.</p>
<div class="links"><a href="https://doi.org/10.5281/zenodo.18280746"><i class="ai ai-zenodo"></i> SSTCI data</a><a href="https://doi.org/10.5281/zenodo.18823611"><i class="ai ai-zenodo"></i> CDHE event catalogue</a><a href="https://doi.org/10.5194/essd-18-7981-2026">ESSD paper</a><a href="https://doi.org/10.5446/74082"><i class="fa-solid fa-circle-play"></i> Video abstract</a></div>
</div>

<div class="dataset">
<h3>Seamless FengYun-3 soil moisture record</h3>
<p>A finer-resolution, temporally consistent surface soil-moisture record built by synergistically merging the FengYun-3 passive-microwave satellite series — the outcome of a decade of retrieval improvements (open-water correction, scattering-albedo updates and correlation-preserving merging) to the Land Parameter Retrieval Model applied to China's FY-3 sensors.</p>
<div class="links"><a href="https://doi.org/10.5281/zenodo.7764786"><i class="ai ai-zenodo"></i> Zenodo record</a><a href="https://doi.org/10.1038/s41597-025-05263-7">Data descriptor (Scientific Data, 2025)</a></div>
</div>

<div class="dataset">
<h3>Long-term global satellite soil moisture from maximized temporal correlations (1998–2015)</h3>
<p>A merged, multi-sensor global satellite soil-moisture record built to preserve temporal correlation across sensors (<em>Remote Sensing</em>, 2020).</p>
<div class="links"><a href="https://doi.org/10.5281/zenodo.3937398"><i class="ai ai-zenodo"></i> Zenodo record</a><a href="https://doi.org/10.3390/rs12132164">Paper (Remote Sensing, 2020)</a></div>
</div>

<div class="dataset">
<h3>Harmonized global land evaporation dataset (1980–2017)</h3>
<p>A harmonised global land-evaporation dataset derived from model-based products, developed with Jiao Lu, Guojie Wang and colleagues.</p>
<div class="links"><a href="https://doi.org/10.5281/zenodo.4595940"><i class="ai ai-zenodo"></i> Zenodo record</a><a href="https://doi.org/10.5194/essd-13-5879-2021">Earth System Science Data (2021)</a></div>
</div>

<div class="dataset">
<h3>Data for “Divergent regional responses of soil moisture–air temperature coupling”</h3>
<p>Data behind the <em>Nature Communications</em> (2026) analysis of how soil moisture–temperature coupling changes under future climate scenarios.</p>
<div class="links"><a href="https://doi.org/10.5281/zenodo.20122978"><i class="ai ai-zenodo"></i> Zenodo record</a><a href="https://doi.org/10.1038/s41467-026-74040-w">Paper (Nature Communications, 2026)</a></div>
</div>

<div class="dataset">
<h3>Time-varying and multivariate Liang–Kleeman information flow</h3>
<p>Causal-inference formalisms for non-stationary climate time series: a time-varying Liang–Kleeman information flow (<em>Journal of Climate</em>, 2019) and its extension to time-dependent multivariate causal structures (<em>Journal of Climate</em>, 2024), with a recent benchmark of conditioning strategies (<em>Earth System Dynamics</em>, 2026) and an application to causal importance in physics-informed machine learning (CLeaR 2026). Two patents cover algorithms developed for causality analysis and extreme-climate evaluation. Code is available on request.</p>
<div class="links"><a href="https://doi.org/10.1175/JCLI-D-18-0881.1">Time-varying LKIF (2019)</a><a href="https://doi.org/10.5194/esd-17-1551-2026">Conditioners benchmark (ESD, 2026)</a><a href="{{ '/Research/' | relative_url }}">Research overview</a></div>
</div>
