# 🎨 2 CHARACTER ART

## Purpose
The visual soul of every Biblical person - from Adam to Revelation's witnesses

## What Goes Here
- Original character sprite artwork (before importing to Unity)
- Multiple versions/states of each character (innocent/fallen, young/old, happy/sad)
- Character portrait art for dialogue scenes
- Animation sprite sheets (walking, praying, fighting)
- Character concept sketches and reference materials
- Work-in-progress Krita/Photoshop files (.kra, .psd)

## Folder Structure Inside
```
2 character art\
├── old_testament\
│   ├── adam\          (adam_innocent.png, adam_fallen.png, adam_old.png)
│   ├── eve\           (eve_innocent.png, eve_mother.png)
│   ├── noah\          (noah_young.png, noah_building.png, noah_ark.png)
│   └── moses\         (moses_prince.png, moses_shepherd.png, moses_leader.png)
├── new_testament\
│   ├── jesus\         (jesus_baby.png, jesus_teaching.png, jesus_crucified.png)
│   ├── apostles\      (peter_fisher.png, peter_apostle.png)
│   └── mary\          (mary_young.png, mary_mother.png)
└── working_files\     (Original .kra files you're editing)
```

## Use Cases
- Your "art studio" - all original artwork created here
- Source files stay here, copies go to Unity
- Character evolution tracking (young David → King David)
- NFT metadata will reference these original files
- Artists collaborate by sharing this folder

## Sprite Specifications
- **Size**: 64x64 pixels (standard), 128x128 (detailed)
- **Format**: PNG with transparency
- **Colors**: Limited palette for retro feel
- **States**: At least 3 per major character
- **Naming**: `charactername_state.png`

## Workflow
1. Create in Krita/GIMP → Save .kra to `working_files\`
2. Export as PNG → Save to character's folder
3. Copy PNG → Import to Unity's Assets folder
4. Keep originals here for editing

## Character Priority List
1. **Essential First**: Adam, Eve, Noah, Moses, David, Jesus
2. **High Priority**: Abraham, Joseph, Mary, Peter, Paul
3. **Medium Priority**: Other apostles, major prophets
4. **Lower Priority**: Minor characters, genealogies