# CNC Resources

This directory is reserved for **CNC-specific resources and machining documentation** for the Venus De Milo platform.

The VDM is designed CNC-first, but machine setup, CAM strategy, tooling, stock, workholding, and controller behavior vary significantly between shops. Resources placed here should therefore be treated as references rather than universal machine-ready instructions.

Planned and appropriate content includes:

- Machining setup notes
- Workholding and registration strategies
- Toolpath guidance
- Recommended operation order
- Feeds / speeds observations tied to specific machines and tooling
- CNC-specific fixtures
- Reference G-code or CAM examples where useful

## Important

Always inspect generated toolpaths and simulate or air-cut unfamiliar programs before machining a workpiece.

Do not assume reference CAM or machining parameters are safe for your router. Verify spindle/router speed, cutter geometry, depth of cut, step-over, workholding, coordinate origin, clearances, and machine travel for your own setup.

Editable project geometry and templates are primarily maintained under [`../docs/`](../docs/).

This directory will expand as repeatable VDM machining workflows are tested and documented.
