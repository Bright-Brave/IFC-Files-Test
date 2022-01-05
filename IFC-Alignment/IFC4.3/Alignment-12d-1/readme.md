
### Intent

This scenario has the IFC semantic definition of an alignment with:

- horizontal straight
- horizontal arc with IFC positive radius of curvature
- horizontal straight

There is no no vertical.
There is no IFC geometry.

![alignment12d1](../Alignment-12d-1/Alignment-12d-1.png  "Alignment with horizontal straight-arc-straight but no vertical") 

The IFC file was generated by 12d Model. 

### Prerequisites

- ProjectSetup-1

### Content

This scenario covers the additional concepts and/or IFC entities:

- `IfcAlignment`
- `IfcAlignmentSegment`
- `IfcAlignmentHorizontal`
- `IfcAlignmentHorizontalSegment` with `PredefinedType=LINE`
- `IfcAlignmentHorizontalSegment` with `PredefinedType=CIRCULARARC` for a left arc
- `IfcRelNests` 

### Supporting files

Following files correspond to this scenario:

| Filename                        | Description                                                                           |
|---------------------------------|---------------------------------------------------------------------------------------|
| `Alignment-12d-1.ifc`        | the exported content as an IFC file                                                   |
| `Alignment-12d-1.png`        | plan view of the alignment, and the horizontal segment parameters (with Civil radius) |

