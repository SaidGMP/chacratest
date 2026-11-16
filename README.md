# ChacraTest
Crop rotation stress-test for the Moquegua highlands (Carumas) using NASA POWER data. NASA Space Apps 2026, challenge "Field Shift: Adapting Farms with NASA Data".
Live page: https://saidgmp.github.io/chacratest/ (Spanish: add #es)
Coordinates: -16.8096, -70.6950. 35 growing seasons (Oct-Apr, 1991-2025) plus a monthly pattern (monthly.json) and a sowing-month planner (monthly_series.json).
Limits: NASA POWER is a coarse grid; thresholds are reference values, not validated locally; seasons are the unit of inference (monthly values are not independent samples).
AI use: an AI assistant (Claude, Anthropic) helped discuss approaches, research background material, review code and text, and draft specific parts: the monthly data script, the sowing-month planner, and the slides. The core analysis code was written by the team, who ran the code and checked the numbers against the data.
Updated: 15 Nov 2026
