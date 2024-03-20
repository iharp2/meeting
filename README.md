# Roadmap

## List of queries
- [ ] Area finding query
  - "find an area A that satisfies a certain criteria"
  - E.g., "find the area that has recorded the maximum temperature each month over the last 10 years."
- [ ] Time period finding query
  - "find a time period T that satisfies a certain criteria"
  - E.g., "find the day with the minimum temperature in every 50km2 of Alaska over the last 5 years."
- [ ] Arbitrary value-based query
  - "retrieve records based on a certain variable criteria"
  - E.g., "find all data records in the world over the last year where the temperature has exceeded 240."
- [ ] Heatmap query
  - "have the heatmap of a certain variable V over a certain area A and certain time period T"
  - E.g., "draw the average temperature heatmap of Green- land over the last year."
- [ ] Time series query
  - "have a time series of a certain variable V over area A and time period T"
  - E.g., "draw the average temperature heatmap of Green- land over the last year."

---

## Action Roadmap

#### pre-aggregation 
- [ ] hard define a pre-aggregation rule (TOML format)
- [ ] a ``do_pre_agg.py`` script
- [ ] 

#### 

---
### Project Policy
1. All project should be name as ``iharp-``.
2. Use Python 3.11 with ``venv`` virtual environment, git ignore ``venv`` folder. 
3. List all packages in ``requirements.txt``.
4. Have a ``init_venv.sh`` to (re-)init virtual environment.  
5. For collaborating repo, use **branch** to contribute. Ask Yuchuan/Youssef for pull request. 
6. For solo repo, better pin Yuchuan/Youssef after a main push. 