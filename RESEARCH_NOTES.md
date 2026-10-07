# Research notes

## Identity

The inspected application identifies itself as **OPP** and its About window includes the wording **"OPP by RFSAC."** The full expansion of the name `OPP` was not found in the inspected build.

The About window credits **Jason Flickinger** as the original developer and **Tim Monzures** as the person who later rewrote and maintained the application.

## Data and plotting features

The inspected build registers CSV as a document type. Its bundle and executable contain references consistent with engineering-test-data analysis, including:

- grouped data plots
- histograms
- cumulative distribution functions (CDFs)
- correlation plots
- time-series plots
- averages
- standard deviations
- specification/test limits
- Cpk values
- counts
- serial-number information
- dataset comparison
- CSV merge operations
- PNG plot export

Resources in the application include names such as `GroupedCDF`, `GroupedCorrelation`, `GroupedData`, `GroupedHistogram`, and `GroupedTimeSeries`.

## RF and hardware-test indicators

The executable contains measurement names associated with RF and hardware testing, including references to:

- frequency units (Hz, kHz, MHz, GHz)
- downlink power
- measured power
- target power
- gain index / analog gain
- antenna serial-number and vendor fields
- VSWR
- EVM-related measurements

These observations support describing OPP as an engineering test-data analysis tool with RF/hardware-test use cases. They do not, by themselves, establish that RF analysis was its only purpose.

## Technical observations

The inspected build was x86_64-only and could launch on Apple Silicon through Rosetta 2 after local quarantine-related launch issues were resolved.

The inspected copy included CorePlot and Sparkle and was signed with an Apple Developer ID identity. The signature verified successfully and a stapled notarization ticket was present.

## Scope of this public archive

This repository intentionally omits internal service addresses, internal mailing-group addresses, private documentation links, the original application bundle, and bundled proprietary frameworks.
