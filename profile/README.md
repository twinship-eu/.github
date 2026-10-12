<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/twinship-eu/.github/main/profile/assets/twinship-logo-dark.png">
  <img src="https://raw.githubusercontent.com/twinship-eu/.github/main/profile/assets/twinship-logo-light.png" alt="TwinShip" width="440">
</picture>

### Integrated Digital Twin Framework to Enable Green Ship Operations Towards Zero-Emission Vessels

[![Horizon Europe](https://img.shields.io/badge/Horizon%20Europe-GA%20101192583-003399?style=flat-square)](https://cordis.europa.eu/project/id/101192583)
[![Project period](https://img.shields.io/badge/2025%20%E2%80%93%202028-project%20period-555?style=flat-square)](https://cordis.europa.eu/project/id/101192583)
[![Website](https://img.shields.io/badge/web-twin--ship.eu-006837?style=flat-square)](https://twin-ship.eu/)
[![Ontology](https://img.shields.io/badge/ontology-ontology.twin--ship.eu-01203A?style=flat-square)](https://ontology.twin-ship.eu/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-TwinShip-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/company/twinship/)
[![YouTube](https://img.shields.io/badge/YouTube-@TwinShipProject-FF0000?style=flat-square&logo=youtube&logoColor=white)](https://www.youtube.com/@TwinShipProject)

</div>

---

**TwinShip** is a Horizon Europe research and innovation project (February 2025 – January 2028) building an **open-source digital platform for the maritime sector**. The platform pairs AI-driven **Digital Twins** with a **Decision Support System (DSS)** so ships can be designed and operated more efficiently. The aim is to cut greenhouse-gas emissions from shipping by 30–40 % by 2030 and 80–90 % by 2040, and to reach net zero by 2045 (all relative to 2008). The work covers existing and emerging clean fuels, renewable energy and unmanned vessels.

The consortium brings together maritime technology providers, shipowners, naval architects, a classification society, a port authority, software developers and research institutes.

## What we are building

| Pillar | Description |
| --- | --- |
| **System-of-Systems Digital Twins** | Integrated digital twin models of four pilot vessels, covering the lifecycle from design to operation. |
| **Open DT/DSS platform** | An open, data-rich platform that hosts digital-twin-enabled decision support. It adapts and extends the [VesselAI](https://platform.vessel-ai.eu/) digital platform and builds in security and privacy. |
| **Vessel Data Cloud Space** | A shared vessel data space built on open data standards, a maritime **ontology** and **knowledge graphs**. |
| **DT model evaluation** | A new methodology and set of standards for evaluating digital twin models, including hardware-in-the-loop testing. |
| **Data quality governance** | Guidelines and tools for detecting, isolating and recovering anomalies in the data that feeds the digital twins. |
| **Green decision support** | Voyage optimisation, environmental impact assessment and lifecycle cost analysis, turning digital-twin insight into operational decisions. |

## Pilot demonstrations

| | Vessel | Partner |
| :-: | --- | --- |
| 1 | RoRo vessel | Grimaldi |
| 2 | RoPax vessel | Stena |
| 3 | Chemical tanker | Stena |
| 4 | Futuristic concept: an unmanned, zero-emission RoRo vessel | |

## Open-source repositories

| Repository | What it does | Stack | License |
| --- | --- | --- | --- |
| [**twinship-ontology**](https://github.com/twinship-eu/twinship-ontology) | A modular OWL ontology for the maritime domain (vessels, onboard systems, weather conditions and more). It includes SHACL validation, WIDOCO documentation and a WebVOWL visualisation. **[Browse it online ›](https://ontology.twin-ship.eu/)** | OWL · Turtle · Python | MIT |
| [**twinship-data-pipeline**](https://github.com/twinship-eu/twinship-data-pipeline) | A Dagster pipeline that harmonises vessel specification data into RDF conforming to the TwinShip ontology. It validates the data with SHACL and publishes the knowledge graph to GraphDB. | Python · Dagster · RDF · GraphDB | CC BY 4.0 |
| [**twinship-3d-visualizer**](https://github.com/twinship-eu/twinship-3d-visualizer) | An interactive, ontology-based 3D viewer of the TwinShip futuristic RoRo vessel. Every component and parameter links back to its formal ontology definition. | TypeScript · Next.js · Three.js | MIT |

```text
              ┌─────────────────────────────┐
              │      twinship-ontology      │
              │   (shared semantic model)   │
              └─────────────────────────────┘
                   ▲                   ▲
       conforms to │                   │ links components
                   │                   │ & parameters
  ┌────────────────┴───────┐   ┌───────┴─────────────────┐
  │ twinship-data-pipeline │   │ twinship-3d-visualizer  │
  └────────────┬───────────┘   └─────────────────────────┘
               ▼
      RDF knowledge graph
      (GraphDB · SPARQL)
```

## Consortium

Coordinated by **[UiT The Arctic University of Norway](https://uit.no/)**, with partners:

SINTEF · Wärtsilä · Institute of Communication and Computer Systems (ICCS) · National Technical University of Athens (NTUA) · American Bureau of Shipping (ABS) · Grimaldi Euromed · Stena · Knud E. Hansen · Fundación Valenciaport · ASSIST Software · UBITECH · 52°North · Bound 4 Blue

→ More about the partners at [twin-ship.eu/consortium](https://twin-ship.eu/consortium)

## Get involved

- **Explore** the [TwinShip ontology](https://ontology.twin-ship.eu/), or run the pipeline and 3D viewer locally by following each repository's README.
- **Report a bug or suggest an improvement** by opening an issue in the relevant repository.
- **Contribute** by following our [contributing guidelines](https://github.com/twinship-eu/.github/blob/main/CONTRIBUTING.md) and [code of conduct](https://github.com/twinship-eu/.github/blob/main/CODE_OF_CONDUCT.md).
- **Stay up to date** through our [news](https://twin-ship.eu/latest-news), [publications](https://twin-ship.eu/publications), [LinkedIn](https://www.linkedin.com/company/twinship/) and [YouTube](https://www.youtube.com/@TwinShipProject).
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
      </sub>
    </td>
  </tr>
</table>
