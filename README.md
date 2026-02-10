# Datathon Project

## Documents Source
https://guides.library.txstate.edu/lovedataweek/datathonchallenge26


# Where Should TXST Recruit?
## Identifying High-Performing Texas Regions for Strategic Student Recruitment

**Datathon Challenge:** Data for Bobcat   
**Date:** February 2026

---

## 🎯 Research Question

**"Where should Texas State University recruit? Identifying high-performing Texas regions currently underserved by universities where TXST has competitive recruitment opportunities."**

This project maps the competitive landscape of Texas higher education and identifies geographic regions where TXST can strategically expand its recruitment efforts to attract talented students.

---

## 📊 Data Sources

### 1. **Texas Public High School SAT/ACT Performance Data (2024)**

**Key Metrics:**
- Number of graduates per school/district/county
- SAT/ACT participation rates
- Percentage scoring above college-readiness criteria
- TSI (Texas Success Initiative) readiness rates
- Demographic breakdowns (ethnicity, economic status, etc.)

**What This Shows:** Where high-performing students are located across Texas

### 2. **Texas Public University SAT/ACT Score Ranges**
**Source:** [College Tuition Compare](https://www.collegetuitioncompare.com/compare/tables/?state=TX&type=public&factor=sat-act-scores)  

**Key Data Points:**
- SAT score ranges (25th, 50th, 75th percentiles)
- ACT score ranges (25th, 50th, 75th percentiles)
- Admission test requirements


**What This Shows:** TXST's competitive positioning and target student profile

### 3. **High School Graduate College Enrollment Data**
**Source:** [Texas Higher Education Coordinating Board (THECB)](https://www.txhighereddata.org/high-school-graduates/hsgradsenrolled/)  
**Platform:** TX Higher Ed Data Interactive Reports  

**Available Data:**
- Where Texas high school graduates enroll (by county/district/school)
- College-going rates by region
- In-state vs out-of-state enrollment patterns
- Enrollment by institution type (2-year vs 4-year, public vs private)

**What This Shows:** Current enrollment patterns and TXST's market share

---

## 🗺️ Analysis Approach

### Phase 1: Map Student Talent Distribution
- Identify counties with high SAT/ACT performance
- Analyze college-readiness rates by region
- Visualize geographic distribution of high-performing students

### Phase 2: Competitive Landscape Analysis
- Calculate distance from each county to major universities
- Map institutional coverage and "education deserts"
- Compare TXST's accessibility to competitors

### Phase 3: Enrollment Pattern Analysis
- Determine where high-performing students currently enroll
- Calculate TXST's market share by region
- Identify regions where competitors dominate

### Phase 4: Opportunity Identification
**Target Profile:**
- Counties with above-average SAT/ACT scores
- Reasonable distance to San Marcos (50-150 miles)
- Currently underserved by major universities
- Lower enrollment rates at UT/A&M (less competition)
- Growing population/demographics

### Phase 5: Strategic Recommendations
- Rank counties by recruitment opportunity score
- Identify specific high schools for targeted outreach
- Propose data-driven recruitment strategies

---

## 📈 Expected Outputs

1. **Interactive Maps:**
   - Texas county map colored by student performance
   - University locations with enrollment capacity
   - TXST's competitive advantage zones

2. **Data Visualizations:**
   - Scatter plots: Distance vs. Enrollment patterns
   - Heatmaps: County performance vs. college choice
   - Bar charts: TXST market share by region

3. **Strategic Report:**
   - Top 10-15 target counties for recruitment
   - Specific high schools with high potential
   - Actionable recruitment recommendations

4. **Digital Poster:**
   - Research question and methodology
   - Key findings and visualizations
   - Strategic recommendations for TXST

---

## 🎓 Significance & Impact

**For Texas State University:**
- Data-driven recruitment strategy
- Competitive intelligence on peer institutions
- Identification of untapped student markets
- Resource allocation optimization

**For Texas Higher Education:**
- Understanding geographic access gaps
- Insights into student migration patterns
- Regional equity in higher education access

**For Students:**
- Better alignment between student qualifications and institutional fit
- Increased awareness of TXST in high-performing regions

---

## 📝 Next Steps

- [ ] Clean and merge all datasets
- [ ] Calculate geographic distances
- [ ] Perform statistical analysis
- [ ] Create geospatial visualizations
- [ ] Develop opportunity scoring model
- [ ] Generate final recommendations
- [ ] Create presentation materials
- [ ] Submit to TXST Dataverse

---

## 📚 References

1. Texas Education Agency. (2024). *SAT/ACT Participation and Performance, Texas Public Schools, Class of 2024*. Retrieved from TEA Reports.

2. Texas Higher Education Coordinating Board. (2024). *High School Graduates Enrolled in Higher Education*. Retrieved from http://www.txhighereddata.org/

3. College Tuition Compare. (2024). *Texas Public Colleges SAT/ACT Scores Comparison*. Retrieved from https://www.collegetuitioncompare.com/

4. Texas Higher Education Coordinating Board. (2024). *Love Data Week Datathon Challenge*. Retrieved from https://guides.library.txstate.edu/lovedataweek/datathonchallenge26

---

## 📂 Repository Structure

```
datathon-project/
├── README.md
├── data/
│   ├── satact-campus-data-class-2024.xlsx
│   ├── texas_public_colleges_sat_act_scores.csv
│   └── thecb_enrollment_data.csv (to be downloaded)
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_geospatial_analysis.ipynb
│   └── 03_visualization.ipynb
├── outputs/
│   ├── maps/
│   ├── figures/
│   └── final_report.pdf
└── presentation/
    └── digital_poster.pdf
```
