# Azure Data Factory Practice

This repository is a starter project for learning and practicing Azure Data Factory (ADF) concepts.

## Purpose

Use this repo to:
- explore ADF pipeline design
- define linked services, datasets, and pipelines
- version-control sample ADF objects
- build a repeatable practice environment

## Repository structure

```text
.
├── .gitignore
├── README.md
├── adf/
│   ├── dataset/
│   │   └── ds_sample_csv.json
│   ├── linkedService/
│   │   └── ls_azure_blob_storage.json
│   └── pipeline/
│       └── pl_copy_sample.json
└── docs/
    └── setup-notes.md
```

## Suggested next steps

1. Add your Azure subscription and environment details.
2. Create or import the actual ADF resource in Azure.
3. Replace the sample pipeline with real copy or transformation flows.
4. Add parameterized datasets and linked services for your data sources.

## Notes

This is intentionally a lightweight starter repo. You can expand it with:
- Dataflows
- Triggers
- SQL scripts
- CI/CD deployment config
- Terraform or Bicep definitions

