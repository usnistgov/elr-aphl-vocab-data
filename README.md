# APHL NIST GVT Reference Data

This repository contains reference data consumed by the NIST Global Validation Tool (GVT) for Association of Public Health Laboratories (APHL) profiles. The data is organized by specific public health laboratory domains and includes value sets, observations, orders, tests, and profile definitions.

## Folder Structure

- **ARLN**: Antimicrobial Resistance Laboratory Network data
  - ARLN master spreadhseet (Excel)
  - Value sets (CSV)
  - Observations, Orders, Tests (CSV)

- **ELR_FOUNDATION**: Electronic Lab Reporting Foundation data
  - SPM-4 data (CSV)

- **PHLIP**: Public Health Laboratory Interoperability Project data
  - PHLIP master spreadhseet (Excel)
  - Value sets (CSV)
  - MSH-3/MSH-4 data (CSV)
  - Observations, Orders, Tests (CSV)

- **Rabies**: Rabies testing profile data
  - Rabies master spreadhseet (Excel)
  - Value sets (CSV)
  - Observations, Orders, Tests (CSV)

- **VPD**: Vaccine Preventable Diseases data
  - VPD master spreadhseet (Excel)
  - Value sets (CSV)
  - SPM-4 data (CSV)
  - Observations, Orders, Tests (CSV)

## File Types

- `.xlsx`: Excel files containing profile definitions and configurations
- `.csv`: Comma-separated value files containing:
  - Value sets: Codified terminology used in the profiles
  - Observations: Clinical observation templates
  - Orders: Laboratory order templates
  - Tests: Laboratory test definitions
  - Element-specific files: HL7 message segment definitions (e.g., SPM-4, MSH-3, MSH-4)

## Usage

This data is intended for use with the NIST GVT tool to validate HL7 v2.5.1 messages against APHL-specific implementation guides. The reference data supports validation of public health laboratory reporting messages including:
- Electronic Laboratory Reporting (ELR)
- Laboratory-specific reporting (ARLN, PHLIP, Rabies, VPD)

## Data Currency

Files are dated and versioned to reflect updates to the reference terminology and profile definitions. Users should ensure they are using the appropriate version for their validation needs.
