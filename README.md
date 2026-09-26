# Web Scraping 101
### Presented by STARS Computing Corps

A 30-minute workshop: collect fictional tech events, build a table, and find free online options.

## Students: start here
1. Open [Google Colab](https://colab.research.google.com/).
2. Choose **File > Upload notebook** and select `notebooks/starter.ipynb` from this kit. If the opening dialog offers Upload, use that instead.
3. Run cells in order. The blank page URL uses bundled practice HTML. The source label tells you which mode you are using.
4. Change the two values in the challenge, then export your results.

You may follow along, work with a neighbor, or watch and make predictions. A Google account and internet access are needed to run in Colab. No local Python setup is required for Colab.

## What is included
| File | Purpose |
| --- | --- |
| `slides/STARS_Web_Scraping_101.pptx` | Editable slides with speaker notes |
| `PRESENTER_GUIDE.md` | Minute-by-minute script, answers, and contingency plan |
| `SETUP.md` | GitHub, Pages, Colab, and rehearsal instructions |
| `notebooks/starter.ipynb` | Participant notebook |
| `notebooks/solution.ipynb` | Completed challenge and answer |
| `docs/index.html` | Fictional practice page, open locally or publish |
| `data/backup.html` | Identical HTML snapshot |
| `data/sample_events.csv` | Expected complete dataset |
| `configure_workshop.py` | Sets notebook URL and creates workshop links |
| `requirements.txt` | Dependencies for optional local use |

## Organizer
Read `SETUP.md`, then rehearse using `PRESENTER_GUIDE.md`. The kit is not yet published to GitHub. For the live HTTP demo, publish the included page and configure its URL. The notebooks can already run with their embedded backup.

## Optional local use
Install packages with `python -m pip install -r requirements.txt`, then open the notebooks in your existing Jupyter environment. Jupyter itself is not included in requirements. Open `docs/index.html` in a browser to inspect its HTML.

## Take-home challenge
Filter for beginner-friendly free online events. Expected result: four events. Try adding a new event to the HTML and scraping it.
