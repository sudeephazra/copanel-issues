# CoPanel Defect Tracking Repository

Welcome to the CoPanel Defect Tracking repository! This repository is dedicated to logging, tracking, and managing defects for the CoPanel software. It is intended for issue tracking only; no source code or other project assets will be stored here.
Purpose

## This repository serves as a centralized location for:
- Reporting defects or bugs encountered in CoPanel.
- Tracking the status, priority, and resolution of defects.
- Documenting any updates, workarounds, or relevant information regarding the issues.

## How to Use This Repository

- Check Existing Issues: Before creating a new issue, please review open issues to avoid duplicates.
- Create New Issue: If the defect hasn’t been reported, create a new issue using the provided templates below.
- Provide Details: When reporting an issue, include as much relevant information as possible to help reproduce and investigate the problem.

## Issue Template

Use the following format when creating a new issue:
#### Title: Brief description of the defect.
#### Description:
- **Summary**: A brief summary of the defect.
- **Steps to Reproduce**: List the steps that led to the defect.
- **Expected Result**: What you expected to happen.
- **Actual Result**: What actually happened.
- **Environment**: Include any relevant details such as the operating system, browser, device, or version information.
- **Additional Context**: Any additional information, screenshots, or logs that might help in understanding the issue.

## Labels:
Use labels such as `bug`, `enhancement`, `priority-high`, `priority-medium`, `priority-low`, etc., to categorize and prioritize issues.

## Examples
### Example Issue:
- **Title**: Dropdown menu in the dashboard does not load options
- **Description**:
- **Summary**: The dropdown menu on the dashboard page fails to display options.
- **Steps to Reproduce**:
  - Log into the CoPanel platform.
  - Navigate to the dashboard.
  - Click on the "CoPanel" icon on the status bar 
- **Expected Result**: The option should display a list of available projects.
- **Actual Result**: The dropdown appears blank with no options.
- **Environment**: Windows 10, Chrome v114.0
- **Additional Context**: Console shows error: TypeError: Cannot read property 'map' of undefined.

## Contributing to Defect Tracking
Everyone is welcome to contribute by reporting defects, adding detailed information to existing issues, or suggesting solutions. Please adhere to the issue template and guidelines to keep this repository organized and effective.
