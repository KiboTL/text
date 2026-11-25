# Azur Promilia localization text

This repository tracks the original client text and the English and Russian translations used to build the localization patches.

- `official/` holds the original strings so changes in future client versions can be reviewed in Git.
- `translations/` holds the `en` and `ru` text.
- `glossary.tsv` records terminology, source references, and review decisions.

Both text directories have the same layout.

| Folder | Contents |
| --- | --- |
| `table/` | Dialogue, quests, item descriptions, HUD hints, and other localized game table entries. |
| `shared/` | Text stored directly in shared game tables, such as skill names and descriptions. |
| `static/` | Static UI text, including menu and button labels. |
| `startup/` | Loading, download, and update messages. The official records retain the shipped language columns. |

Each JSONL line holds one string record. A table ID such as `pc_button_hint:77309411584` identifies the table and row.
