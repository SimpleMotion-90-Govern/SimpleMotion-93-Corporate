<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/SimpleMotion-99-Templates/.github/main/profile/sm-assets/sm-white-banner.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/SimpleMotion-99-Templates/.github/main/profile/sm-assets/sm-black-banner.svg">
    <img alt="SimpleMotion" src="https://raw.githubusercontent.com/SimpleMotion-99-Templates/.github/main/profile/sm-assets/sm-black-banner.svg" width="800">
  </picture>
</p>

<p align="center">
  <em>Engineered for Architecture, Entertainment and Industry.</em>
</p>

## Project Template

This is the **SimpleMotion Project Template** (990005-ST-99-Default-SimpleMotion-Project).

Use this template when creating new project repositories via `/sm-project`.

### Folder Structure

```
project-repo/
├── .claude/              # Claude AI configuration (submodule)
├── .simplemotion/        # Local data storage (not tracked)
├── 10-Engage/            # Client engagement documents
│   ├── 11-Client/        # Documents from client
│   ├── 12-SimpleMotion/  # Assets (logo, signature)
│   ├── 13-Quotation/     # Quotation documents
│   ├── 14-Expenses/      # Internal cost analysis
│   ├── 15-Invoices/      # Invoice documents
│   ├── 18-Metadata/      # Project metadata (.toml)
│   └── 19-Templates/     # Document templates
├── 20-Manage/            # Project management
├── 30-Design/            # Engineering design
├── 40-Create/            # Manufacturing/procurement
├── 50-Deploy/            # Deployment/handover
├── 80-Corpus/            # Reference materials
├── 90-Govern/            # Governance
├── ASSIGNMENT.md         # IP assignment
├── CHANGELOG.md          # Version history
├── CLAUDE.md             # Project context
├── LICENSE.md            # MIT License
└── README.md             # This file
```

### After Creating from Template

1. Update `CLAUDE.md` with project details
2. Rename `10-Engage/18-Metadata/PROJECT-ID-18-Metadata.toml`
3. Update metadata TOML with client and project information
4. Run `/sm-commit "Initial project setup" --push`
