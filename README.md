# Seif Abroud

**Data Science · Machine Learning · LLM Agents**

I'm a Data Science master's student at ISI Mahdia (University of Monastir, Tunisia), with a bachelor's degree in Computer Science and a background in software development. My work sits between modelling and engineering: I take a loosely defined question, build the pipeline that answers it, and make sure every result can be traced back and checked.

Recent work covers retail demand forecasting driven by LLM agents, geospatial clustering on open data, and document processing with OCR. Most of my projects ship as something you can run, such as a dashboard, an app or a reproducible notebook, not only as an analysis.

---

### Selected projects

| Project | What it does | Stack |
|---|---|---|
| **[Decision agents](https://github.com/SeifAbroud/decision-agents-gemini)** | Multi-agent decision support for retail (Favorita). A global LightGBM model forecasts 1,782 store × product series 16 days ahead with p10/p90 intervals. LangGraph agents then analyze, recommend and report, and a critic agent rejects any figure that isn't backed by logged evidence. | LightGBM · LangGraph · RAG · Streamlit · Pandas |
| **[Tunisia solar priority zones](https://github.com/SeifAbroud/Tunisia-solar-priority-zones)** | Screens all of Tunisia for zones worth studying for solar PV. 1,659 grid cells built from open geospatial data, six clustering models compared, and a 100-cell shortlist stress-tested over 1,000 random weightings. With Ghezlen Ben Abdrahmen. | scikit-learn · K-Means · HDBSCAN · Earth Engine · OpenStreetMap |
| **Document management system** *(private, ISIMA)* | Secure local platform for a university administration: e-signatures, role-based access, a PostgreSQL data model, and OCR that classifies scanned documents and extracts their fields. | Django · PostgreSQL · Tesseract OCR · Vue.js |
| **[dukkani](https://github.com/FindMalek/dukkani)** *(contribution)* | Open-source no-code online shop builder. Merged pull request. | TypeScript |

### How I work

- **Numbers come from code, not from the model.** In my agent systems the LLM computes nothing: deterministic tools produce every figure, and each one is logged as evidence.
- **Real data, or no data.** Gaps stay gaps. I would rather report a missing value than fill it with something invented.
- **Beat a baseline first.** Forecasts are compared with seasonal-naive and moving-average references before any claim is made.
- **State the limits.** Every project README says what the work does not tell you.

### Tools I built

Small utilities that automate my own workflows:
[WeTransfer-Automation](https://github.com/SeifAbroud/WeTransfer-Automation) (Selenium upload and share-link pipeline) ·
[litterwatch](https://github.com/SeifAbroud/litterwatch) (folder watcher with automatic upload) ·
[image-copyright-stamper](https://github.com/SeifAbroud/image-copyright-stamper) (batch metadata writer, ExifTool) ·
[Directory-organizer](https://github.com/SeifAbroud/Directory-organizer) (rule-based file sorting)

### Stack

**Data & ML** Python, Pandas, NumPy, scikit-learn, LightGBM, R, statistics, time series<br>
**LLM systems** LangGraph, tool use, retrieval (RAG)<br>
**Data engineering** SQL, PostgreSQL, Neo4j, Talend (ETL), KNIME, Parquet<br>
**Visualization** Power BI, Streamlit, Matplotlib<br>
**Software** Django, REST APIs, Vue.js, Node.js, Docker, Redis, Git

---

**Education** MSc Data Science, ISI Mahdia (2025–2027) · BSc Computer Science, ISI Mahdia (2022–2025), Highest Honors<br>
**Languages** Arabic · English (C1) · French<br>
**Contact** abroudseif@gmail.com · [LinkedIn](https://www.linkedin.com/in/seif-abroud-28107a245/)
