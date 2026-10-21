# Project Afterlight

**Abandoned, but not forgotten.** A mobile-friendly educational website about 12 NASA missions and the science they left behind.

Made by **Team Echonova** for the NASA Space Apps Challenge 2026 challenge *"Abandoned but Not Forgotten: Storytelling about NASA's Discarded Equipment on the Moon and Mars."*

**Live site:** https://gangakb933-design.github.io/afterlight/

> Independent educational project. Not affiliated with NASA. Images and science are NASA-sourced; see Credits.

## What it is

- **Cinematic opening:** a space introduction where you choose Moon, Mars or Deep space. Each destination changes the colors and mood of the site.
- **12 mission stories:** each told in five chapters (Arrival, The mission, The evidence, The last signal, What remains), with facts, a quiz and NASA source links.
- **Reconnect the Signal:** a short interactive puzzle (tune a signal, rebuild the communication chain) that decodes a real mission fact. The puzzle is fictional; the facts are real.
- **Status badges:** Silent, Parked, Grounded, Switched off, or Still talking.
- **Timeline, map, glossary and explorer passport** (stamps are earned by passing mission quizzes).
- **Optional sound:** generated in the browser, off by default.

## Missions

| Mission | Where | Status |
| --- | --- | --- |
| Apollo 11 | Moon | Parked |
| Surveyor 3 | Moon | Silent |
| Opportunity | Mars | Silent |
| Spirit | Mars | Silent |
| Sojourner | Mars | Silent |
| Voyager 1 | Deep space | Still talking |
| Apollo science stations | Moon | Switched off |
| Lunar Roving Vehicles | Moon | Parked |
| Viking 1 and 2 | Mars | Silent |
| Phoenix | Mars | Silent |
| Ingenuity | Mars | Grounded |
| Pioneer 10 | Deep space | Silent |

Voyager 1 is included as a contrast: it is not abandoned.

## How it is built

A single `index.html` file with plain HTML, CSS and JavaScript. No build step, no frameworks, no external libraries. Photos sit beside it in the same folder. Progress (passport stamps, decoded transmissions) is saved in the browser's local storage. Hosted on GitHub Pages.

To run locally, open `index.html` in a browser.

## Image credits

All photographs are from NASA. Credit lines are shown with each image on the site.

| NASA ID | Image | Credit |
| --- | --- | --- |
| AS11-40-5948 | Aldrin and the Early Apollo Scientific Experiments Package | NASA |
| AS12-48-7136 | Conrad examines Surveyor 3 | NASA |
| PIA10077 | Opportunity's arm in Victoria Crater | NASA/JPL-Caltech |
| PIA17760 | Husband Hill panorama (Spirit) | NASA/JPL-Caltech/Cornell Univ. |
| PIA00968 | Sojourner APXS at 'Stimpy' | NASA/JPL |
| PIA17464 | Voyager 1 launch, September 5, 1977 | NASA/KSC |
| PIA00563 | First color image from the Viking 1 lander | NASA/JPL |
| PIA11718 | Phoenix lander with surrounding terrain, vertical projection | NASA/JPL-Caltech/University of Arizona/Texas A&M University |
| PIA25881 | Ingenuity at two years on Mars | NASA/JPL-Caltech/ASU/MSSS |
| ARC-1972-AC72-2134 | Pioneer F (Pioneer 10) delivered to NASA at Cape Kennedy | NASA |
| AS14-67-9361 | Apollo 14 ALSEP central station and mortar package | NASA |
| AS17-137-20979 | Apollo 17 lunar roving vehicle with repaired fender | NASA |

## Accuracy

Mission facts link to NASA sources on each mission page. Please report any error through the repository's issues.

## Team

Team Echonova.
