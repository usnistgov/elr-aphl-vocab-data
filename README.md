<<<<<<< HEAD
# APHL NIST GVT Reference Data

This repository contains reference data consumed by the NIST Global Validation Tool (GVT) for Association of Public Health Laboratories (APHL) profiles. The data is organized by specific public health laboratory domains and includes value sets, observations, orders, tests, and profile definitions.

## Folder Structure

- **ARLN**: Anthrax Reference Laboratory Network data
  - Profile definitions (Excel files)
  - Value sets (CSV)
  - Observations, Orders, Tests (CSV)

- **ELR_FOUNDATION**: Electronic Lab Reporting Foundation data
  - SPM4 Value Set (CSV)

- **PHLIP**: Public Health Laboratory Interoperability Project data
  - Profile definitions (Excel files)
  - Value sets (CSV/Excel)
  - MSH3/MSH4 segments (CSV)
  - Observations, Orders, Tests (CSV)

- **Rabies**: Rabies testing profile data
  - Profile definitions (Excel)
  - Value sets (CSV)
  - Observations, Orders, Tests (CSV)

- **VPD**: Vaccine Preventable Diseases data
  - IGAMT (Immunization Gateway Assessment and Monitoring Tool) VPD profiles (Excel)
  - VPD profile definitions (Excel)
  - Value sets (CSV)
  - SPM4 segment (CSV)
  - Observations, Orders, Tests (CSV)

## File Types

- `.xlsx`: Excel files containing profile definitions and configurations
- `.csv`: Comma-separated value files containing:
  - Value sets: Codified terminology used in the profiles
  - Observations: Clinical observation templates
  - Orders: Laboratory order templates
  - Tests: Laboratory test definitions
  - Segment-specific files: HL7 message segment definitions (e.g., SPM4, MSH3, MSH4)

## Usage

This data is intended for use with the NIST GVT tool to validate HL7 v2.5.1 messages against APHL-specific implementation guides. The reference data supports validation of public health laboratory reporting messages including:
- Electronic Laboratory Reporting (ELR)
- Immunization Information Systems (IIS)
- Laboratory-specific reporting (Anthrax, Rabies, VPD)

## Data Currency

Files are dated and versioned to reflect updates to the reference terminology and profile definitions. Users should ensure they are using the appropriate version for their validation needs.
