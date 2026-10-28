# Business-Intelligence
## Tools and methods
Built with **Power BI** (Power Query, DAX), delivered as a single interactive `.pbix` report with 14 tabs,
one per indicator, viewable on desktop and mobile. Each tab has a descriptive title, key conclusions, an
illustrative visual and the data source.

**Data model**
- Star-style model loading only the required tables and fields, without many-to-many relationships
- Custom **date table** with hierarchies, covering all days needed for the analysis
- Custom **geography table** with a country, continent hierarchy used to compare regions

**Power Query (M)**
- Parameterised queries, so data sources can be switched
- Documented transformation steps, reusable for new datasets

**DAX**
- Explicit measures only (no implicit aggregations), including measures for indicators that arrive as percentages
- Advanced functions such as `CALCULATE`, `FILTER`, `VALUES` and `LASTDATE` for deeper insights
- Each analysis has its own dataset, DAX measure and visual

**Scope**
- Several indicators cover all continents and time spans longer than a decade (up to 2000-2022)
- Storytelling structure: title, conclusion, supporting visual, source
