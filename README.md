# AC Repair Assistant

**AI-powered AC Error Code Diagnostic System** for inverter and non-inverter ACs.

## Problem
AC technicians waste time looking up error codes across different brands and manuals.  
This tool gives instant diagnosis, likely causes, and repair steps in one place.

## What it does
- Diagnoses error codes for 19 AC brands including LG, Samsung, Daikin, Midea, Gree
- Explains likely causes in plain language
- Lists step-by-step repair solutions
- Supports both inverter and non-inverter systems

## Who it’s for
Junior AC technicians, field technicians, and service centers who need fast, reliable troubleshooting without flipping through manuals.

## Tech Stack
Python, FastAPI, MSSQL

## How to run
1. Clone the repo
2. Install requirements: `pip install -r requirements.txt`
3. Run: `python main.py`

## Example
**Input:** Brand = LG, Code = CH05, Mode = Inverter  
**Output:** Communication error → Check wiring between indoor and outdoor units → Verify cable connections

## Why it matters
- Covers 400+ error codes across major brands
- Cuts diagnosis time from 15 min to under 2 min
- Reduces mistakes for new technicians

## Screenshots
![App running](add-screenshot-here.png)

## What I learned
Built this to practice Python, data structuring, and CLI design. It shows I can take a real-world problem, break it down, and build a working solution.
