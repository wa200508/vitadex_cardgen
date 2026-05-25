# vitadex_cardgen
Trading card generation mechanism for VitaDex

## Extracted database assets
- `database/database.py` contains the shared card database model and sample entries.
- `database/card_database_schema.json` is the JSON schema for new card entries.
- `database/openwebui_card_prompt.txt` provides the prompt template for generating compliant entries.
- `card_generation/workflow_api.json` stores the ComfyUI workflow payload.
- `scripts/download_models.py` downloads the checkpoints referenced by the workflow.
