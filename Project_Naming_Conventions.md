# Green AI Solutions: File Naming Conventions

## Overview

This document outlines the standardized naming conventions used throughout the Green AI Solutions project. Following these conventions ensures consistency, makes files easier to locate, and facilitates project maintenance and integration.

## General Principles

1. **Descriptive Names**: All file names should clearly indicate their content and purpose
2. **Word Separation**: Use underscores (_) to separate words in filenames
3. **Lowercase**: Use lowercase for standard files (with exceptions noted below)
4. **No Spaces**: Avoid spaces in file and directory names
5. **Consistent Terminology**: Use consistent terms across related files
6. **Appropriate Extensions**: Use appropriate file extensions that reflect file type

## Directory Naming

Directories follow these naming conventions:

1. **Main Directories**: Use CamelCase (e.g., `Business_Strategy`, `HR_Automation`)
2. **Subdirectories**: Use CamelCase (e.g., `Market_Analysis`, `System_Architecture`)
3. **Descriptive Purpose**: Directory names should reflect the category of contained files
4. **Consistent Structure**: Maintain parallel structure across similar directories

## Markdown File Naming

Markdown (.md) files follow these naming conventions:

1. **Lowercase with Underscores**: Use lowercase with underscores between words (e.g., `market_analysis_dual_hr_systems.md`)
2. **Title Case for Main Documents**: Use title case for primary documents (e.g., `Project_Structure.md`)
3. **Descriptive Content**: Filename should indicate the specific content
4. **Versioning**: Version indicators should be included when multiple versions exist (e.g., `compliance_framework_v2.md`)
5. **Date Indicators**: Include dates in filenames only when date is a key identifying element (e.g., `editorial_calendar_2026.md`)

## Image File Naming

Image files (.png, .jpg, etc.) follow these naming conventions:

1. **Lowercase with Underscores**: Use lowercase with underscores between words (e.g., `hr_dashboard_mockup.png`)
2. **Content Description**: Filename should describe what is shown in the image
3. **Type Indicator**: Include indicators of image type (e.g., `mockup`, `diagram`, `screenshot`)
4. **Version Indicators**: Include version indicators when multiple versions exist (e.g., `mobile_dashboard_mockup_v2.png`)
5. **State Indicators**: Include state indicators when showing different states (e.g., `employee_quick_add_fixed.png`)

## Code File Naming

Code files (.html, .css, .js, etc.) follow these naming conventions:

1. **Lowercase with Hyphens**: Use lowercase with hyphens between words for web assets (e.g., `lead-capture.js`)
2. **Lowercase with Underscores**: Use lowercase with underscores for other code files (e.g., `roi_calculator_prototype.py`)
3. **Purpose Indicator**: Filename should indicate the file's purpose or functionality
4. **Component Naming**: Component files should be named after the component they implement

## README Files

README files follow these naming conventions:

1. **All Capitals**: Use `README.md` for all readme files
2. **One Per Directory**: Include one README file in each main directory and subdirectory
3. **Content Description**: README should describe the purpose and contents of the directory
4. **Related Files**: Include references to related files in other directories

## Special File Types

1. **Templates**: Include `template` or `_template` in the filename (e.g., `case_study_template.md`)
2. **Checklists**: Include `checklist` in the filename (e.g., `launch_preparation_checklist.md`)
3. **Guides**: Include `guide` in the filename (e.g., `business_listings_setup_guide.md`)
4. **Plans**: Include `plan` in the filename (e.g., `launch_preparation_plan.md`)
5. **Strategies**: Include `strategy` in the filename (e.g., `disruptive_pricing_strategy.md`)

## Examples by Category

### Business Documents
- market_analysis_dual_hr_systems.md
- financial_projections_dual_hr_systems.md
- australian_market_entry_strategy.md

### Technical Specifications
- hr_automation_blueprint.md
- unified_hr_system_architecture.png
- system_integration_diagram.png

### Marketing Materials
- content_marketing_strategy.md
- lead_capture_implementation_plan.md
- editorial_calendar_2025_2026.md

### Website Files
- index.html
- styles.css
- lead-capture.js

### Design Files
- neurodivergent_hr_system_concept.md
- command_center_dashboard.png
- interface_toggle_component.png

## File Organization

Files should be organized according to the standard directory structure outlined in [Project Directory Structure](Project_Directory_Structure.md). The full index of project files categorized by purpose is available in [Project File Index](Project_Management/Project_File_Index.md).

## Metadata Standards

All documentation files should include standard metadata at the end:

```
---

**Document Metadata**
- Version: [version number, e.g., 1.0]
- Creation Date: [initial creation date]
- Last Updated: [last modification date]
- Owner: [document owner or team]
- Status: [Active, Draft, Archived, etc.]
```

## Versioning Approach

When updating files, follow these versioning practices:

1. **Minor Updates**: For minor content edits, update the "Last Updated" date
2. **Major Updates**: For significant content changes, increment the version number
3. **Version Tracking**: Major versions should be tracked in the [Document Registry](Documentation/document_registry.md)
4. **Archiving**: When replacing a document with a new version, archive the old version rather than deleting it

## File Naming Don'ts

1. **Don't use spaces** in filenames
2. **Don't use special characters** (!, @, #, $, %, etc.) in filenames
3. **Don't use unnecessarily long** filenames
4. **Don't use ambiguous abbreviations** that may be unclear to others
5. **Don't include irrelevant information** in filenames

---

**Document Metadata**
- Version: 1.0
- Creation Date: May 7, 2025
- Last Updated: May 7, 2025
- Owner: Tom Green
- Status: Active