# Huynh Thanh Nghi — Game Producer · Lead Game Designer

Site: **https://nghihuynh0212.github.io/**

Organized by role. One folder per role, each holding a CV and a portfolio.

## Producer / Lead Game Designer — primary

| Item | Link |
|---|---|
| Portfolio (web) | [nghihuynh0212.github.io](https://nghihuynh0212.github.io/) |
| Portfolio (PDF, 23 pages A4) | [GameProducer_Portfolio.pdf](https://nghihuynh0212.github.io/producer/HuynhThanhNghi_GameProducer_Portfolio.pdf) |
| CV (PDF, 2 pages) | [GameProducer_CV.pdf](https://nghihuynh0212.github.io/producer/HuynhThanhNghi_GameProducer_CV.pdf) |

## LiveOps & Game Design

| Item | Link |
|---|---|
| Portfolio (web) | [/liveops/](https://nghihuynh0212.github.io/liveops/) |
| Portfolio (PDF) | [LiveOps_Portfolio.pdf](https://nghihuynh0212.github.io/liveops/HuynhThanhNghi_LiveOps_Portfolio.pdf) |
| CV (2 pages) | [PDF](https://nghihuynh0212.github.io/liveops/HuynhThanhNghi_LiveOps_CV.pdf) · [DOCX](https://nghihuynh0212.github.io/liveops/HuynhThanhNghi_LiveOps_CV.docx) |

## Game Designer

| Item | Link |
|---|---|
| Portfolio 日本語 (web) | [/game-designer/](https://nghihuynh0212.github.io/game-designer/) |
| Portfolio English (web) | [/game-designer/index-en.html](https://nghihuynh0212.github.io/game-designer/index-en.html) |
| Portfolio 日本語 (PDF, 22 pages A4) | [Portfolio_JP.pdf](https://nghihuynh0212.github.io/game-designer/HuynhThanhNghi_Portfolio_JP.pdf) |
| Portfolio English (PDF) | [GameDesigner_Portfolio.pdf](https://nghihuynh0212.github.io/game-designer/HuynhThanhNghi_GameDesigner_Portfolio.pdf) |
| CV English (2 pages) | [PDF](https://nghihuynh0212.github.io/game-designer/HuynhThanhNghi_GameDesigner_CV.pdf) · [DOCX](https://nghihuynh0212.github.io/game-designer/HuynhThanhNghi_GameDesigner_CV.docx) |
| 履歴書 | [PDF](https://nghihuynh0212.github.io/game-designer/HuynhThanhNghi_%E5%B1%A5%E6%AD%B4%E6%9B%B8.pdf) · [DOCX](https://nghihuynh0212.github.io/game-designer/HuynhThanhNghi_%E5%B1%A5%E6%AD%B4%E6%9B%B8.docx) |
| 職務経歴書 (PDF) | [職務経歴書.pdf](https://nghihuynh0212.github.io/game-designer/HuynhThanhNghi_%E8%81%B7%E5%8B%99%E7%B5%8C%E6%AD%B4%E6%9B%B8.pdf) |

## BrSE

| Item | Link |
|---|---|
| Portfolio English (web) | [/brse/](https://nghihuynh0212.github.io/brse/) |
| CV + Portfolio English (PDF, 11 pages) | [BrSE_CV_Portfolio_EN.pdf](https://nghihuynh0212.github.io/brse/HuynhThanhNghi_BrSE_CV_Portfolio_EN.pdf) |
| CV English (DOCX) | [BrSE_CV_EN.docx](https://nghihuynh0212.github.io/brse/HuynhThanhNghi_BrSE_CV_EN.docx) |
| 履歴書・職務経歴書 (6 pages) | [PDF](https://nghihuynh0212.github.io/brse/HuynhThanhNghi_%E5%B1%A5%E6%AD%B4%E6%9B%B8%E3%83%BB%E8%81%B7%E5%8B%99%E7%B5%8C%E6%AD%B4%E6%9B%B8_BrSE.pdf) · [DOCX](https://nghihuynh0212.github.io/brse/HuynhThanhNghi_%E5%B1%A5%E6%AD%B4%E6%9B%B8%E3%83%BB%E8%81%B7%E5%8B%99%E7%B5%8C%E6%AD%B4%E6%9B%B8_BrSE.docx) |

## Notes

- Folders are named by role, not by employer. The employer mapping lives in Drive only.
- Root `index.html` is the Producer portfolio; each role folder's `index.html` is that role's web portfolio (`brse/index.html` is the English BrSE portfolio).
- `.nojekyll` is present so Jekyll does not process these files.

### Known issue — unpaginated portfolio PDFs

Three portfolio PDFs were exported as a single continuous page roughly 3 m tall
instead of A4 pages, so they cannot be printed and read poorly in most viewers:

- `liveops/HuynhThanhNghi_LiveOps_Portfolio.pdf` (825 × 8736 pt)
- `game-designer/HuynhThanhNghi_GameDesigner_Portfolio.pdf` (825 × 8841 pt)
- the Drive copy of the Producer portfolio (825 × 8430 pt) — **not used here**;
  this repo serves the 23-page A4 export instead.

`HuynhThanhNghi_Portfolio_JP.pdf` (22 pages A4) shows the correct output.

## Legacy URLs (compatibility)

Links shared before the 2026-09-23 reorganisation still resolve, so no document
that has already been sent out needs reissuing.

- Legacy `.html` paths are real redirect stubs at their old addresses. They
  return 200 and redirect in any client.
- Legacy `.pdf` / `.docx` paths are handled by `404.html`, which maps the old
  path to the new one and redirects. Static hosting cannot serve a redirect
  under a `.pdf` content type, so this works in a browser but not for scripted
  downloads (`curl`, `wget`).

The map is the `MOVED` object in `404.html`. Add a line there whenever a
published file moves.
