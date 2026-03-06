# System Architecture

```
Customer Call Transcript
          │
          ▼
   Data Extraction Script
 (extract_data.py)
          │
          ▼
    Account Memo JSON
   (account_memo.json)
          │
          ▼
   Agent Generator
 (generate_agent.py)
          │
          ▼
   Agent Specification
   (agent_spec_v1.json)
          │
          ▼
  Agent Update Script
  (update_agent.py)
          │
          ▼
 Updated Agent Spec
  (agent_spec_v2.json)
          │
          ▼
     Change Log
     (changes.md)
```
