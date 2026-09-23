# Huynh Thanh Nghi — Game Producer · Lead Game Designer

Site: **https://nghihuynh0212.github.io/**

Organized by role. One folder per role, each holding a CV and a portfolio.

## Producer / Lead Game Designer — primary

| Item | Link |
|---|---|
| Portfolio (web) | https://nghihuynh0212.github.io/ |
| Portfolio (PDF, 23 pages A4) | https://nghihuynh0212.github.io/producer/HuynhThanhNghi_GameProducer_Portfolio.pdf |
| CV (PDF, 2 pages) | https://nghihuynh0212.github.io/producer/HuynhThanhNghi_GameProducer_CV.pdf |

## LiveOps & Game Design

| Item | Link |
|---|---|
| Portfolio (web) | https://nghihuynh0212.github.io/liveops/ |
| Portfolio (PDF) | https://nghihuynh0212.github.io/liveops/HuynhThanhNghi_LiveOps_Portfolio.pdf |
| CV (PDF / DOCX, 2 pages) | https://nghihuynh0212.github.io/liveops/HuynhThanhNghi_LiveOps_CV.pdf |

## Game Designer

| Item | Link |
|---|---|
| Portfolio 日本語 (web) | https://nghihuynh0212.github.io/game-designer/ |
| Portfolio English (web) | https://nghihuynh0212.github.io/game-designer/index-en.html |
| Portfolio 日本語 (PDF, 22 pages A4) | https://nghihuynh0212.github.io/game-designer/HuynhThanhNghi_Portfolio_JP.pdf |
| Portfolio English (PDF) | https://nghihuynh0212.github.io/game-designer/HuynhThanhNghi_GameDesigner_Portfolio.pdf |
| CV English (PDF / DOCX, 2 pages) | https://nghihuynh0212.github.io/game-designer/HuynhThanhNghi_GameDesigner_CV.pdf |
| 履歴書 (PDF) | https://nghihuynh0212.github.io/game-designer/HuynhThanhNghi_履歴書.pdf |
| 職務経歴書 (PDF) | https://nghihuynh0212.github.io/game-designer/HuynhThanhNghi_職務経歴書.pdf |

## BrSE

| Item | Link |
|---|---|
| 履歴書・職務経歴書 (PDF / DOCX, 6 pages) | https://nghihuynh0212.github.io/brse/HuynhThanhNghi_履歴書・職務経歴書_BrSE.pdf |

## Notes

- Folders are named by role, not by employer. The employer mapping lives in Drive only.
- Root `index.html` is the Producer portfolio; each role folder's `index.html` is that role's web portfolio.
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
