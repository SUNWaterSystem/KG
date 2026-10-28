# CCR KG system: saved test runs for team review

The goal is one reusable knowledge-graph generation system. Wang and Sun are
development tests used to expose shared system limitations and guide improvements.
This delivery is an offline browsing snapshot of the saved Sun test run, plus
its original input/output archive. It is not a new Sun-specific system and does
not run new extraction in the browser.

## Review the saved result

Download [Sun_KG_Offline_Viewer.zip](packages/Sun_KG_Offline_Viewer.zip), extract
the entire archive, and double-click Open_Sun_KG.html. The original dark interface
structure, five tabs, metric definitions, filtering rules, graph colors, and
default graph scope are retained. Original Wang-specific labels remain visible
so teammates can identify the current system's gaps. Offline differences are
described below and in the package README.

The complete initial graph has 98 nodes and 109 relation candidates, all still
pending/demo_only. The exact original graph mapping and entity-ID helper are used.
Layout coordinates may differ; browser downloads replace USB writes. Server
actions are visible but disabled. The package includes unchanged selected system
source references; it is not the executable runtime.

## Trace inputs and outputs

[Sun_KG_Inputs_Outputs.zip](packages/Sun_KG_Inputs_Outputs.zip) contains the original
PDF, actual three-file profile, all nine model requests/prompts and answers,
response schemas, execution/validation records, and saved aggregate outputs.
This archive is unchanged from the first delivery. body-* denotes the original
generic body-extraction tasks, not new graph content. Wang uses specialized task
names including narrative for body extraction.

## Scope and evidence

Packaging does not run extraction, modify the source system, or approve scientific claims. The 109 candidates contain 5 dissolvesIn, 34 usedInProcess,
and 70 hasProperty relations. Study context is simulation in 101 and uncertain
in 8; engineering validation is not independent scientific evaluation.

The included paper is Sun, M., Gao, X., Zhang, Z., Zou, C., Xin, D., & Geng, G.
(2023), Stepwise dissolution of silica surface in alkaline solution revealed by
molecular modeling, Journal of the American Ceramic Society 106, 6586–6601,
DOI 10.1111/jace.19355. Its original Attribution-NonCommercial notice is retained.
Cytoscape.js retains its MIT license. See notices inside each ZIP.

[SHA256SUMS.txt](SHA256SUMS.txt) records archive hashes. Internal manifests record
file integrity. [VERIFICATION.json](VERIFICATION.json) records offline checks.

## Week16 workflow report

[Download/read the Week16 HTML report](week16/week16_CCR_KG_Workflow.html)
and keep [Sun_claim_example.json](week16/Sun_claim_example.json) beside it for
the complete candidate example. The HTML embeds all diagrams and styles.
The Markdown version is in
[GroupMeeting / Xiaowei_Report](https://github.com/SUNWaterSystem/GroupMeeting/blob/main/Xiaowei_Report/week16_CCR_KG_Workflow.md).
Historical source/run file links require the original local project volume.
