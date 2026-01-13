# 7-Phase Literature Review Workflow

## Phase 1: Project Initialization

Create project structure:
```
project_root/
├── CLAUDE.md              # Writing guidelines
├── IMPLEMENTATION_PLAN.md # Staged plan
├── manuscript_draft.md    # Main manuscript
└── figures/               # Figure placeholders
```

**Actions:**
1. Create `CLAUDE.md` from template (see TEMPLATES.md)
2. Create `IMPLEMENTATION_PLAN.md` with stages
3. Initialize empty `manuscript_draft.md`

## Phase 2: Literature Collection

**Actions:**
1. Connect to Zotero API (if available)
2. Search academic databases (PubMed, IEEE, Springer)
3. Categorize papers by method/application
4. Create literature matrix:

| Category | Subcategory | Key Papers | Count |
|----------|-------------|------------|-------|
| Methods  | CNN/U-Net   | [refs]     | N     |
| Methods  | Transformer | [refs]     | N     |
| Clinical | Validation  | [refs]     | N     |

5. Identify gaps requiring more literature

## Phase 3: Outline Development

**Actions:**
1. Define section headings based on literature categories
2. Map papers to sections
3. Plan comparison tables
4. Design figure placeholders

**Output:** Detailed outline in IMPLEMENTATION_PLAN.md

## Phase 4: Section Writing

For each major section:

1. **Write introduction** (1-2 paragraphs on motivation)
2. **Describe methods** using standard template
3. **Add performance data** with consistent metrics
4. **Write limitations** paragraph
5. **Create comparison table**
6. **Update references**

**Progress tracking:** Use TodoWrite for each section

## Phase 5: Tables and Figures

**Required tables:**
- Table 1: Public Datasets
- Table 2: Method Comparison
- Table 3: Commercial Products (if applicable)

**Figure placeholders:**
- Figure 1: Review overview/taxonomy
- Figure 2: Method evolution timeline
- Figure 3: Representative architectures
- Figure 4: Clinical workflow

## Phase 6: Quality Assurance

**Structure check:**
- [ ] Key Points present
- [ ] All sections have summary tables
- [ ] Consistent heading hierarchy

**Content check:**
- [ ] All major methods covered
- [ ] Limitations discussed
- [ ] Future directions articulated

**Language check:**
- [ ] Hedging language used
- [ ] Terminology consistent
- [ ] Transitions smooth

**Reference check:**
- [ ] 80-120 references
- [ ] Recent literature included
- [ ] Organized by topic

## Phase 7: Incremental Updates

When new literature becomes available:

1. **Categorize** new papers
2. **Update CLAUDE.md** reference sources
3. **Update IMPLEMENTATION_PLAN.md** with new stage
4. **Identify insertion points** in manuscript
5. **Update sections** with new methods
6. **Add new sections** if new paradigm emerges
7. **Update tables** with new data
8. **Expand references**

**Version control:**
```markdown
## Change Log
### [Date] - v1.1
- Added Section 3.X [New Category]
- Updated Table 2 with N new methods
- Added references #XX-#YY
```
