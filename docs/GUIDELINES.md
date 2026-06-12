# File Submission Guidelines

## Quality Standards

### Accuracy
- All dimensions must be verified against original specifications or physical measurements
- Tolerance levels should be clearly specified
- Include measurement methodology and tools used

### File Format Requirements

#### DXF Files (2D)
- Created for CNC compatibility
- Clean geometry with no overlapping lines
- Proper layer organization
- Scale: 1:1 (full size)
- Units clearly specified (mm or inches)

#### 3D Models (STEP, IGES, STL)
- Include both solid bodies and feature definitions
- Proper material assignments where applicable
- Organized into logical components
- Include all mounting holes and references

#### Documentation
- PDF specifications with technical drawings
- Bill of materials if applicable
- Assembly sequence diagrams
- Photos of original parts (reference)

## Folder Organization

### Projects Folder Example
```
Projects/
├── Galaga/
│   ├── CAD/
│   │   ├── SidePanel.dxf
│   │   ├── SidePanel.pdf
│   │   └── SidePanel_3D.step
│   ├── Specs/
│   │   └── SidePanel_Specifications.md
│   └── Assembly/
│       └── Assembly_Guide.md
├── Pacman/
└── [ArcadeTitle]/
```

## Naming Best Practices

- Use descriptive names that clearly identify the part
- Include version numbers for iterations
- Use underscores for spacing (not spaces)
- Keep filenames under 50 characters when possible

Example Good Names:
- `Galaga_SidePanelLeft_v2.dxf`
- `PacMan_MoneyDoor_Specifications.pdf`
- `DonkeyKong_BeamAssembly_v1_3D.step`

## Verification Checklist

Before submitting, verify:

- [ ] All files are in correct formats
- [ ] Dimensions are accurate and verified
- [ ] File names follow naming conventions
- [ ] Documentation is complete
- [ ] References/source materials are noted
- [ ] Files are organized in appropriate folders
- [ ] No copyrighted material without permission
- [ ] Safety warnings included if needed

