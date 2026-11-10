# Cyprus Company Registry: Directors & Secretaries MCP

Search the Cyprus Registrar of Companies and see who is behind a company: directors, secretaries, business-name owners, partners and authorized persons, including former officers.

The MCP connection is provided by [The Company Atlas](https://thecompanyatlas.com). This repository does not run a separate server.

## Connect

```
https://thecompanyatlas.com/mcp/company/cyprus
```

Add this URL as a custom MCP connector in Claude, ChatGPT, Cursor, or any MCP-compatible client. Sign in with Google when prompted.

- Transport: Streamable HTTP
- Auth: Google OAuth (sign in once, stays authorized)
- Free accounts get 50 credits per calendar month

## Cyprus data coverage

- Companies, overseas companies, business names and partnerships
- Company ids are `CY` + type letter (`C` company, `O` overseas company, `B` business name, `P` partnership) + registration number
- Greek and English names, registration date, status and status date
- Current and former officers, with English position titles (e.g. Alternate Director)

## Example prompts

- *"Who are the directors and secretary of this Cyprus company?"*
- *"Which Cyprus companies is this person a director of?"*
- *"Show the former directors of this Limassol holding company"*
- *"Find Cyprus companies with 'Shipping' in the name"*

## Tools

| Tool | Description |
|---|---|
| `Cyprus_search_companies` | Search companies in the Cyprus registry by name or id |
| `Cyprus_get_company` | Full company profile by id (the `CY` prefix is optional) |
| `Cyprus_search_people` | Officers and shareholders by person name or company, and every company a person is tied to |

## Ελληνικά

Στοιχεία από το Τμήμα Εφόρου Εταιρειών για τον ψηφιακό σας βοηθό: αναζητήστε εταιρείες, εμπορικές επωνυμίες και συνεταιρισμούς, και δείτε διευθυντές, γραμματείς, συνεταίρους και πρώην αξιωματούχους.

**Παραδείγματα ερωτήσεων**

- *"Ποιοι είναι οι διευθυντές αυτής της εταιρείας;"*
- *"Σε ποιες εταιρείες είναι διευθυντής αυτό το πρόσωπο;"*

## Keywords

Cyprus company search, Cyprus Registrar of Companies, Cyprus directors search, Cyprus offshore company, Μητρώο Εταιρειών, Έφορος Εταιρειών
