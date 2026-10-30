# Dedicated UAM Corridor Design in São Paulo — RIDITA 2026

Public research page: https://orbolato.github.io/ridita-uam-corridor-design/

## Paper

**L. O. Carvalho, J. F. Rodrigues, M. C. R. Murça, D. A. Pamplona, and M. X. Guterres**, “A methodological procedure and supporting tool for dedicated urban air mobility corridor design in the São Paulo metropolitan region,” *X Congreso Internacional de la RIDITA*, La Plata, Argentina, 2026.

The manuscript was accepted for RIDITA 2026 (November 16–18). The page does not claim that proceedings are published or that a DOI has been assigned.

## Supporting tool and reproducibility

The supporting software is the **SIGMA-Sky UAM Airspace Dashboard**. It remains in the project repository rather than being duplicated here.

- [Live dashboard](https://projetosigmasky.github.io/uam_airspace/)
- [Source code and public data](https://github.com/projetosigmasky/uam_airspace)
- [Exact software release cited in the paper: ridita-2026.2](https://github.com/projetosigmasky/uam_airspace/releases/tag/ridita-2026.2)
- [RIDITA verification scripts](https://github.com/projetosigmasky/uam_airspace/tree/main/ridita2026)
- [Author publications](https://orbolato.github.io/publications/)

**Data restrictions:** The dashboard and derived airspace / airport-flow-envelope files are public. Frozen UAM scenario CSVs are available on request. Raw Flightradar24 trajectories are licensed and are not redistributed.

## Local files to add

The original project package contains `paper.pdf`, `slides.pdf`, and figure / logo assets. These binary attachments must be uploaded through GitHub's **Add file → Upload files** interface if not already present. The webpage is functional without them, and its publication metadata will not point to a missing PDF.

After uploading PDFs, update the landing-page links if desired. You may copy them from the project package prepared in ChatGPT.

## GitHub Pages

Open **Settings → Pages → Build and deployment** and choose **Deploy from a branch**, `main` and `/(root)`.

## Citation

Use [CITATION.cff](CITATION.cff) for the conference-paper metadata. For work that uses the dashboard or datasets, also cite the tagged software release rather than the continuously updated live version.
