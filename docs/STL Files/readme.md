# Venus De Milo STL Files

This directory contains **STL mesh exports derived from Venus De Milo CAD/reference files**.

The files are organized by major instrument component:

- [`body/`](body/) — body-related STL exports
- [`neck/`](neck/) — neck, fretboard, nut, and related STL exports

## Revision Warning

The editable SketchUp/CAD files in the repository continue to evolve. STL files are exports and can become stale when the source geometry changes.

Before printing, generating CAM, or using an STL as dimensional authority:

1. Confirm that the file represents the variant you intend to build.
2. Check critical dimensions against the current source CAD.
3. Verify scale, neck-pocket, bridge, pickup, and hardware geometry for your specific build.
4. Inspect the mesh after import into your slicer or CAM software.

When source geometry changes, these STL exports should be regenerated so the repository does not quietly accumulate obsolete manufacturing files.

For editable project geometry, see the parent [`docs/`](../) directory.
