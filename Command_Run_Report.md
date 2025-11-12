# Command Line Test Execution Report

## Project
JSONPlaceholder API Stress Test — Apache JMeter 5.6.3

## Command Used
"/c/apache-jmeter-5.6.3/apache-jmeter-5.6.3/bin/jmeter.bat" \
-n -t "/c/JMeter-Projects/JSONPlaceholder-JMeter-Test/Stress_Test_Plan.jmx" \
-l "/c/JMeter-Projects/JSONPlaceholder-JMeter-Test/results.jtl" \
-e -o "/c/JMeter-Projects/JSONPlaceholder-JMeter-Test/HTMLReport"

## Execution Summary
- Mode: Non-GUI (CLI)
- Plan: Stress_Test_Plan.jmx
- Results File: results.jtl
- Log File: jmeter.log
- HTML Report Folder: /HTMLReport
- Status: Successfully executed
- Warnings: Deprecation messages (safe to ignore)

## Result
Test executed successfully via CLI.
Output files created:
- results.jtl — detailed execution log
- HTMLReport — visual summary report
- jmeter.log — full execution log

## Screenshots
1. Command execution in Git Bash
2. Generated files in project folder

Author: Ivan Savchenko
Date: 12.11.2025
