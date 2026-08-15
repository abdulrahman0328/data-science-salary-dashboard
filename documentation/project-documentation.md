# Project Documentation

## 1. Project Goal

Build an interactive Excel dashboard to analyze data science job-market information and make salary and job-demand patterns easier to explore.

## 2. Dataset

The workbook contains 32,672 job-posting records.

The main dataset includes information such as job title, location, job platform, employment type, country, salary, company, and skills.

## 3. Analysis Structure

### datasets
Contains the main source data.

### basic calculations
Contains helper calculations, unique lists, sorting, and lookup logic used by the dashboard.

### jobs
Supports job-title salary comparisons and dashboard chart calculations.

### Country
Supports country-level salary analysis.

### type
Supports employment-type salary comparisons.

### platform
Supports job-platform analysis and job-posting counts.

### Dashboard
Combines the analysis into an interactive user-facing view.

## 4. Interactive Filters

The dashboard uses three main selections:

- Job Title
- Country
- Employment Type

Changing these selections updates the displayed analysis.

## 5. Important Note

The project is an analytical portfolio project. Results shown on the dashboard depend on the selected filters and the available salary data in the source dataset.
