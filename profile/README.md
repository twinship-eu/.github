<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/twinship-eu/.github/main/profile/assets/twinship-logo-dark.png">
  <img src="https://raw.githubusercontent.com/twinship-eu/.github/main/profile/assets/twinship-logo-light.png" alt="TwinShip" width="420">
</picture>

### Integrated Digital Twin Framework to Enable Green Ship Operations Towards Zero-Emission Vessels

Home of the **VesselAI platform**, a single secure workspace for maritime digital twins, data and AI.

[![Horizon Europe](https://img.shields.io/badge/Horizon%20Europe-GA%20101192583-003399?style=flat-square)](https://cordis.europa.eu/project/id/101192583)
[![VesselAI platform](https://img.shields.io/badge/platform-VesselAI-4318FF?style=flat-square)](https://platform.vessel-ai.eu/)
[![Website](https://img.shields.io/badge/web-twin--ship.eu-006837?style=flat-square)](https://twin-ship.eu/)
[![Ontology](https://img.shields.io/badge/ontology-ontology.twin--ship.eu-01203A?style=flat-square)](https://ontology.twin-ship.eu/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-TwinShip-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/company/twinship/)
[![YouTube](https://img.shields.io/badge/YouTube-@TwinShipProject-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://www.youtube.com/@TwinShipProject)

**[Platform](#the-vesselai-platform)** · **[Capabilities](#what-you-can-do)** · **[Why VesselAI](#why-vesselai)** · **[Roadmap](#roadmap)** · **[Open source](#open-source-components)** · **[Project](#the-twinship-project)** · **[Contact](#get-involved)**

</div>

---

**TwinShip** is a Horizon Europe research and innovation project (2025–2028) that helps the maritime sector move to zero-emission shipping. Its core result is the **VesselAI platform**, a web workspace where shipowners, ship designers and data scientists combine vessel data, AI models and digital twins to make better design and operational decisions. Typical questions it answers include:

- *Which speed minimises cost and emissions on this voyage?*
- *How is the ship performing against its digital-twin baseline?*
- *How much fuel would a wind-assisted concept vessel running on ammonia burn on this route?*

## The VesselAI platform

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/twinship-eu/.github/main/profile/assets/vesselai-logo-dark.png">
  <img align="right" width="150" src="https://raw.githubusercontent.com/twinship-eu/.github/main/profile/assets/vesselai-logo-light.png" alt="VesselAI – maritime digitalisation">
</picture>

**VesselAI is a unified digital-twin and AI workspace designed specifically for maritime analytics.** Everything runs in the browser. Data storage, notebooks, pipelines, models, AI assistants and digital twins come pre-configured and connected behind one sign-in. Teams can focus on analysis and decisions instead of running infrastructure.

The platform was first developed in the Horizon 2020 project [VesselAI](https://vessel-ai.eu/) (grant agreement 957237). TwinShip is adapting and extending it with system-of-systems digital twins, a shared vessel data space and decision-support tools for greener ship design and operation.

<br clear="right">

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/twinship-eu/.github/main/profile/assets/vesselai-platform-dark.svg">
    <img src="https://raw.githubusercontent.com/twinship-eu/.github/main/profile/assets/vesselai-platform-light.svg" alt="VesselAI platform at a glance: users reach Digital Twin Studio, AI Services, Data Analytics, and Data Space and Governance through one web portal with single sign-on, fed by vessel, weather, design and partner data." width="100%">
  </picture>
</p>

## What you can do

<table>
<tr>
<td width="50%" valign="top">

### Digital Twin Studio

- **EPCD Explorer** (Engine–Propeller Combinator Diagram): physics-based estimates of RPM, shaft power, fuel use, CO₂ and NOₓ for any vessel condition and sea state.
- **What-if simulator**: vary speed, draft, trim, heading, propeller pitch, wind and waves, and check NOₓ against IMO MARPOL Annex VI Tier I/II/III.
- **Voyage planning**:
  - plan port-to-port routes across ~4,000 ports that follow real shipping lanes
  - set a target arrival time, or upload your own voyage as a CSV
  - get fuel, CO₂ and NOₓ totals for the whole voyage
- **Decision graphs**: cost-vs-time trade-offs and engine-load profiles. Total cost vs speed highlights the cheapest speed, with wind-assisted propulsion on or off.

</td>
<td width="50%" valign="top">

### AI Services

- **Notebooks**:
  - a private JupyterLab workspace, plus a library of curated examples
  - publish to your team, review changes side by side and share them back
- **AI Workflows**: turn a notebook into a production pipeline, then chain and schedule jobs and follow run metrics over time.
- **AI Models**: run pre-trained maritime models, such as vessel-position prediction and voyage CO₂ estimation, by uploading a CSV.
- **AI Agents**: build chat assistants and agents without code, based on your own documents, and publish them as web apps or APIs.

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Data Analytics

- **Data Requests**: order vessel positions and telemetry, Copernicus and ECMWF weather and ocean data, or both matched along the vessel's track. No code is needed.
- **Data Exploration**: a visual query builder with spatial filters you draw on a map, plus time and value filters. Join datasets and save queries.
- **SQL Studio**: run SQL over the platform's data lake.
  - schema browser
  - one-click ingest that turns raw files into tables
  - charts and export
- **Data Streaming**: publish and follow live operational events such as AIS and weather feeds.

</td>
<td width="50%" valign="top">

### Data Space & Governance

- **Object Storage**: browse, preview and download files. Shared links check the viewer's role, and encrypted data is clearly marked.
- **Access policies**: set per-dataset rules for which roles can decrypt and read the data. The rules are built into the data itself.
- **Per-company isolation**: each shipping company's data, vessels and team notebooks are visible only to the roles they were shared with.
- **VesselAI Assistant**: an in-app helper that answers questions from the documentation, cites its sources and can even plan a voyage.

</td>
</tr>
</table>

### See it in action

<p align="center">
  <img src="https://raw.githubusercontent.com/twinship-eu/.github/main/profile/assets/screens/epcd-explorer.png" alt="EPCD Explorer showing a vessel's actual vs. predicted speed, RPM, shaft power and fuel rate" width="100%">
  <br><sub><b>EPCD Explorer</b>: live performance compared with the digital-twin baseline (demo data)</sub>
</p>

<table>
<tr>
<td width="50%" align="center">
  <img src="https://raw.githubusercontent.com/twinship-eu/.github/main/profile/assets/screens/ai-workflows.png" alt="AI Workflows page listing scheduled and chained pipeline jobs">
  <br><sub><b>AI Workflows</b>: notebooks promoted to scheduled, chained pipelines</sub>
</td>
<td width="50%" align="center">
  <img src="https://raw.githubusercontent.com/twinship-eu/.github/main/profile/assets/screens/notebooks.png" alt="Notebook Environment with personal, shared and example notebooks">
  <br><sub><b>Notebooks</b>: private, team-shared and curated example notebooks</sub>
</td>
</tr>
</table>

### A typical workflow

1. **Sign in once.** Single sign-on opens every tool your role allows.
2. **Get data.** Order vessel and weather datasets or upload your own. Your company's data is encrypted and readable only by authorised roles.
3. **Explore.** Query visually or with SQL, preview the results and export them.
4. **Build.** Develop and test models in your private notebook, and collaborate with your team.
5. **Automate.** Promote notebooks to scheduled pipelines, and track runs and models in the registry.
6. **Decide.** Use the Digital Twin Studio to simulate scenarios, plan voyages and compare cost and emissions.

## Why VesselAI

<table>
<tr>
<td width="33%" valign="top">
<b>Built for ships, not generic data</b><br>
Vessel-specific digital twins, checks against MARPOL emission limits, scenarios for alternative fuels and wind-assisted propulsion, and data models aligned with a maritime ontology.
</td>
<td width="33%" valign="top">
<b>Physics meets AI</b><br>
Physics-based engine–propeller models work alongside data-driven machine learning. Results stay explainable and grounded in naval-architecture fundamentals.
</td>
<td width="33%" valign="top">
<b>Your data stays yours</b><br>
Partner data is encrypted per company, and access rules travel with each dataset. Every company's vessels, data and notebooks are isolated by role.
</td>
</tr>
<tr>
<td width="33%" valign="top">
<b>One workspace, zero setup</b><br>
Data, notebooks, pipelines, models, agents and digital twins are pre-integrated behind one sign-in, so nothing needs to be installed. Operators get no-code tools, and data scientists get full notebooks and SQL.
</td>
<td width="33%" valign="top">
<b>From notebook to production</b><br>
An exploratory notebook becomes a scheduled, monitored pipeline without being rewritten. Experiments, models and runs are tracked in one place.
</td>
<td width="33%" valign="top">
<b>Shaped by industry pilots</b><br>
Developed with shipowners, designers and technology providers, and being validated on RoRo, RoPax and chemical-tanker vessels and a zero-emission concept ship.
</td>
</tr>
</table>

<sub>The platform is built on proven open-source technology (JupyterLab, MLflow, Dagster, Trino and Dify) and on open semantic-web standards (OWL, SHACL and QUDT) through the TwinShip ontology.</sub>

## Roadmap

These modules are being developed in TwinShip and will be added to the platform:

| Module | What it will do |
| --- | --- |
| **Vessel Data Cloud Space** | Explore vessel data as a connected knowledge graph, built on shared ontologies so the same terms mean the same thing in every tool. |
| **ML & AI digital-twin models** | Cluster operating conditions and learn regression models from telemetry, combined with the physics-based twins. |
| **Data quality governance** | Detect anomalies in the data feeding the twins and show how records are flagged, corrected or excluded. |
| **Model evaluation methodology** | Compare model versions on consistent, repeatable criteria, including hardware-in-the-loop testing. |
| **Voyage optimisation** | Weather routing with just-in-time arrival. |
| **LCCA & EIA** | Life-cycle cost analysis and environmental impact assessment of fuels and technologies. |
| **Technology profile analysis** | Compare retrofit and newbuild options using both cost and environmental results. |

> **Platform access:** the VesselAI platform is currently operated for TwinShip partners and pilot users at **[platform.vessel-ai.eu](https://platform.vessel-ai.eu/)**.
> Interested in a demo, a pilot or a collaboration? Contact us at **[info@twin-ship.eu](mailto:info@twin-ship.eu)**.

## Open-source components

| Repository | What it does | Stack | License |
| --- | --- | --- | --- |
| [**twinship-ontology**](https://github.com/twinship-eu/twinship-ontology) | A modular OWL ontology for ships and their onboard systems: engines, propellers, energy storage, fuels, wind-assisted propulsion and more. It has 58 classes and 170 data properties, and builds on ISO 15926-14, QUDT and the VesselAI ontology. **[Browse it online ›](https://ontology.twin-ship.eu/)** | OWL · SHACL · Python | MIT |
| [**twinship-data-pipeline**](https://github.com/twinship-eu/twinship-data-pipeline) | Harmonises vessel specification data into RDF that conforms to the ontology, validates it with SHACL and publishes the knowledge graph to GraphDB. | Python · Dagster · RDF | CC BY 4.0 |
| [**twinship-3d-visualizer**](https://github.com/twinship-eu/twinship-3d-visualizer) | An interactive 3D viewer of the TwinShip futuristic RoRo vessel. Each component and parameter links to its formal definition in the ontology. | TypeScript · Next.js · Three.js | MIT |

## The TwinShip project

TwinShip brings together leading maritime technology providers, shipowners, naval architects, a classification society, a port and research institutes. Together they are building a digital-twin-enabled Decision Support System for green ship operations. The project is working towards cutting greenhouse-gas emissions from shipping by **30–40 % by 2030** and **80–90 % by 2040**, and reaching **net zero by 2045** (all relative to 2008).

| Pilot | Vessel | Partner |
| :-: | --- | --- |
| 1 | RoRo vessel | Grimaldi |
| 2 | RoPax vessel | Stena |
| 3 | Chemical tanker | Stena |
| 4 | Futuristic concept: an unmanned, zero-emission RoRo vessel with wind-assisted propulsion | |

**Coordinator:** [UiT The Arctic University of Norway](https://uit.no/)<br>
**Partners:** SINTEF · Wärtsilä · Institute of Communication and Computer Systems (ICCS) · National Technical University of Athens (NTUA) · American Bureau of Shipping (ABS) · Grimaldi Euromed · Stena · Knud E. Hansen · Fundación Valenciaport · ASSIST Software · UBITECH · 52°North · Bound 4 Blue

More about the project: **[objectives](https://twin-ship.eu/objectives)** · **[consortium](https://twin-ship.eu/consortium)** · **[publications](https://twin-ship.eu/publications)** · **[CORDIS](https://cordis.europa.eu/project/id/101192583)**

## Get involved

- **Explore** the [TwinShip ontology](https://ontology.twin-ship.eu/), or run the open-source components locally using each repository's README.
- **Report a bug or suggest an improvement** by opening an issue in the relevant repository.
- **Contribute** by following our [contributing guidelines](https://github.com/twinship-eu/.github/blob/main/CONTRIBUTING.md) and [code of conduct](https://github.com/twinship-eu/.github/blob/main/CODE_OF_CONDUCT.md).
- **Stay up to date** through our [news](https://twin-ship.eu/latest-news), [LinkedIn](https://www.linkedin.com/company/twinship/) and [YouTube](https://www.youtube.com/@TwinShipProject).
- **Get in touch** at [info@twin-ship.eu](mailto:info@twin-ship.eu).

---

<table>
  <tr>
    <td width="110" align="center">
      <img src="https://raw.githubusercontent.com/twinship-eu/.github/main/profile/assets/eu-flag.png" alt="Flag of the European Union" width="90">
    </td>
    <td>
      <sub>
        <b>Funded by the European Union</b> under the Horizon Europe programme, grant agreement No 101192583.
        Views and opinions expressed are however those of the author(s) only and do not necessarily reflect those of the
        European Union or the European Climate, Infrastructure and Environment Executive Agency (CINEA).
        Neither the European Union nor the granting authority can be held responsible for them.
        <br><br>
        The VesselAI platform was originally developed in the VesselAI project, which received funding from the European Union's
        Horizon 2020 research and innovation programme under grant agreement No 957237.
      </sub>
    </td>
  </tr>
</table>
