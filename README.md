# HDM
HDM Final Project

Overview:
This SQL script provides a workflow to analyze Warfarin patient data, adherence, International Normalized Ratio (INR) control, and identifying missed or delayed doses and their impact on INR levels. The workflow involves creating intermediate tables and performing queries to give user insights into Warfarin dosing and INR monitoring.

How To Use:
Run each section sequentially in a SQL-compatible environment to build the analysis tables. Then, run analysis queries.

Key Tables:
sbapph_warfarin_patients: Warfarin-prescribed patients
sbapph_warfarin_inr_results: INR lab results for these patients
sbapph_missed_inr_tests: Flags for missed INR tests
sbapph_warfarin_dose_timing: Timing of doses relative to schedules
sbapph_inr_control: Categorized INR levels
sbapph_dose_inr_analysis: Links dose adherence with INR outcomes
