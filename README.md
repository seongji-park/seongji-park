# ⚾ Seongji Park — Baseball Analytics

**Statistics @ York University | Statcast Research | Toronto Blue Jays**

I build daily Statcast-based game reports tracking every pitch thrown by Blue Jays pitchers — arsenal breakdowns, pitch tunneling scores, run values, and bullpen performance trends. All analysis is updated after every game throughout the 2026 season.

---

## 🔄 Daily Workflow
Every game produces a full analytical report covering pitch arsenal grades, movement profiles, tunneling analysis, run value breakdowns, spray charts, WPA moments, and bullpen detailed analysis.

---

## 📊 Projects

### Daily Operations
| Repository | Description | Status |
|-----------|-------------|--------|
| [bluejays-daily-reports](https://github.com/seongji-park/bluejays-daily-reports) | Daily Statcast game reports with pitch-level analysis | 🟢 Updated every game |
| [statcast-database](https://github.com/seongji-park/statcast-database) | SQLite pipeline — 15,000+ pitches across 60+ games | 🟢 Updated every series |

### Machine Learning
| Repository | Description | Key Result |
|-----------|-------------|------------|
| [mlb-pitch-prediction](https://github.com/seongji-park/mlb-pitch-prediction) | Per-pitcher RandomForest classifiers predicting next pitch type | Gausman 54.7% accuracy (baseline 52.5%) |
| [mlb-bullpen-forecaster](https://github.com/seongji-park/mlb-bullpen-forecaster) | GradientBoosting classifier for bullpen outing quality | 73.0% accuracy, AUC 0.713 |

### Research
| Repository | Description |
|-----------|-------------|
| [korean-players-mlb-analysis](https://github.com/seongji-park/korean-players-mlb-analysis) | Four-tier analytical framework for Korean MLB players with "Two Pathways" framing |
| [bluejays-2026-pitching-analysis](https://github.com/seongji-park/bluejays-2026-pitching-analysis) | Statcast-driven rotation and bullpen depth assessment |
| [mlb-pitch-design-revolution](https://github.com/seongji-park/mlb-pitch-design-revolution) | League-wide pitch design trends: sweeper explosion, arsenal diversification |

---

## 🛠️ Tech Stack

**Data:** Python · pandas · numpy · pybaseball · SQLite · SQL

**ML:** scikit-learn · RandomForest · GradientBoosting · LogisticRegression

**Visualization:** matplotlib · seaborn

**Tools:** Jupyter Notebook · Git · GitHub

---

## 📈 What the Reports Track

Each game report analyzes every pitch with these metrics:

- **Pitch Arsenal Grades** — Whiff%, CSW%, chase rate → A/B/C/D grading per pitch type
- **Pitch Tunneling** — Release similarity, plate separation, tunnel scores for every pitch pair
- **Run Value** — Per-pitch run value to measure actual run prevention, not just swing-and-miss
- **Bullpen Breakdown** — Individual reliever grades, workload tracking, development arcs
- **Spray Charts & Batted Ball** — Exit velocity, launch angle, hard-hit rate, directional tendencies
- **Win Probability Analysis** — Key WPA moments that swung the game

---

*Built with Statcast data via pybaseball. All pitch metrics sourced from Baseball Savant.*
