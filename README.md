# Data-Analysis
Analysis of Vodafone Users' fluxes : data analysis project for the 1st year course Laboratory of Computational Physics at the MSc in Physics of Data
# Urban Mobility Analysis: Padova Traffic Flows

[![Data Analysis](https://img.shields.io/badge/Analysis-Urban_Mobility-blue?style=for-the-badge)]

Statistical analysis of human mobility patterns in Padova, Italy using anonymized mobile carrier data to inform urban planning and transportation infrastructure decisions.

## 🎯 Objective

This project analyzes urban mobility patterns in Padova using Vodafone network data to identify critical bottlenecks in local transportation and recommend infrastructure improvements. The analysis covers visitor flows, commuter patterns, and distance-based mobility relationships across Italian provinces.

## 📊 Dataset Overview

**Data Source**: Vodafone Italia mobile network analytics  
**Period**: February - May 2018 (4 months)  
**Geographic Scope**: Padova and surrounding Italian provinces  
**Privacy Protection**: Aggregated data with minimum 30-unit threshold

### Core Data Files

| File | Description |
|------|-------------|
| `day_od.csv` | Origin-destination flows by day of week |
| `distinct_users_day.csv` | Unique user counts by origin location |
| `codici_istat_comune.csv` | Municipality code mappings |
| `codici_istat_provincia.csv` | Provincial code mappings |
| `codici_nazioni.csv` | National code mappings |

### External Data Integration
- ISTAT population statistics by province
- Geographic distances between Padova and Italian provinces
- Highway network topology (A13, A4 corridors)

## 🔍 Analysis Framework

### 1. Data Preprocessing
- CSV file validation and standardization
- Geographic code matching with ISTAT references
- Data quality assessment and missing value handling

### 2. International Visitor Analysis
- Ranking of top 20 foreign countries by visitor volume
- Temporal patterns in international tourism flows

### 3. Domestic Mobility Patterns
- Provincial visitor rankings weighted by population density
- Identification of primary catchment areas

### 4. Highway Corridor Analysis
Core transportation network evaluation across three major axes:
- **South Corridor (A13)**: Bologna-Roma direction
- **West Corridor (A4)**: Milano-Torino direction  
- **Northeast Corridor (A4)**: Venezia-Trieste direction

**Analysis Components**:
- Mid-range mobility focus (regional scale)
- Weekend vs. weekday flow differentiation
- Commuter vs. visitor pattern separation
- Infrastructure investment prioritization

### 5. Distance-Mobility Relationship
- Distribution analysis of visitor volume by origin distance
- Statistical model identification and fitting
- Regression analysis for visitor prediction

### 6. Predictive Modeling
- Distance-based visitor flow regression
- Model validation and residual analysis
- Identification of top 5 anomalous provinces (over/under-performing)




## 🎯 Research Applications

### Urban Planning
- Traffic flow optimization
- Public transport route planning
- Commercial district development

### Transportation Engineering  
- Highway capacity planning
- Intersection improvement prioritization
- Multi-modal connectivity enhancement

### Economic Development
- Tourism infrastructure investment
- Business location optimization
- Regional economic integration analysis

## 📊 Data Privacy & Ethics

This analysis uses aggregated, anonymized mobile network data with strict privacy protections:
- No individual user identification possible
- Compliant with EU GDPR regulations
- Used solely for academic/planning purposes



### Data Sources
- Vodafone Italia (Primary mobility data)
- ISTAT (Demographic and geographic data)
- Italian Ministry of Infrastructure

## 📚 References

[1] Italian National Institute of Statistics (ISTAT) - Provincial Demographics  
[2] Vodafone Analytics - Urban Mobility Insights Methodology  
[3] European Commission - Digital Single Market Strategy  
[4] Padova Municipality - Urban Mobility Plan 2018-2025

## 📄 License

This project is licensed under the MIT License. Data usage complies with Vodafone Italia data sharing agreements and GDPR requirements.


