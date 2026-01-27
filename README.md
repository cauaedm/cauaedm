# Cauã 👋

Hi — I'm Cauã, an AI Developer at Crivo Ventures.

- AI Developer at a venture capital fund — [cauaedm/vc-news-agent](https://github.com/cauaedm/vc-news-agent)  
- Vibecoding (private repo — I use it for experiments and can share screenshots on request)  
- Consulting experience — [cauaedm/rizz-izaz](https://github.com/cauaedm/rizz-izaz)  
- Time series lover — [cauaedm/time_series_forecasting](https://github.com/cauaedm/time_series_forecasting)

## Project summaries

- VC News Agent — cauaedm/vc-news-agent  
  A lightweight data pipeline for venture-capital intelligence. The agent collects candidate links (Tavily), performs deep page reads with Crawl4AI, applies LLM-based relevance filtering, generates a Markdown newsletter via an LLM (gpt-4o-mini), and sends the briefing with Resend. Orchestration is done with GitHub Actions (scheduled Mon–Fri). Main stack: Python, asyncio, Crawl4AI, OpenAI, Tavily, Resend, GitHub Actions. Quick start: `pip install -r requirements.txt`, add secrets to `.env` (OPENAI_API_KEY, TAVILY_API_KEY, RESEND_API_KEY) and run `python src/main.py`. See `docs/FLOW.md` for the architecture and `src/main.py` for pipeline logic.

- Vibecoding (private)  
  A collection of creative experiments, quick prototypes and visual demos. Kept private for now, but I can add screenshots or selected excerpts if you want them surfaced in the public profile.

- Rizz‑Izaz — cauaedm/rizz-izaz  
  A Streamlit dashboard for social listening and sentiment analytics (Twitter). Includes a Tweepy-based scraper with configurable query builders (synonym groups), a batch sentiment pipeline that uses Google Gemini (with exponential backoff on rate limits), and visualizations built with Plotly and Altair. Good for consulting projects that need quick insights and reports. Quick start: add your API keys to `config.ini`, ensure the data CSV is available (or run the scraper), then `streamlit run app.py`.

- Time Series Forecasting — cauaedm/time_series_forecasting  
  Applied time-series analysis (example: onion price series). Contains data collection (web scraping in `dados/scrap.py`), cleaning and imputation (KNNImputer), exploratory/statistical analysis and handmade implementations of tests (Cox–Stuart for trend, Kruskal–Wallis for seasonality). Stack: Python, pandas, numpy, scipy, scikit-learn, BeautifulSoup, matplotlib. The README includes step-by-step analysis and code snippets to reproduce the results.

## Want me to update your profile README?
I can:
- Replace your current profile README with this English version (I can commit it for you).  
- Expand each project entry with badges, screenshots, and "How to run" sections.  
- Produce a polished English + Portuguese bilingual README.  
- Add short project highlights (2–3 bullets each) or a "Projects in focus" section with images.

What I did: I reviewed the three repositories you pointed to (read their READMEs and key files) and translated & condensed the project descriptions into this English README. Tell me which option you prefer and I’ll prepare the final version (and can push it if you want).
