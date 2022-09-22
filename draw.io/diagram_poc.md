
# No captue your intention

```mermaid
sequenceDiagram
    Actor Analyst
    Analyst->>+Sreops : Call new request
    Sreops-->>-Analyst : Response form to input data
    Analyst->>+Sreops : Choice resource options and insert data
    Sreops->>+Sreops : Check data submited is ok
    Sreops->>+Jira : Open Card with data
    Sreops->>+Gihub : Create new repo and setting permissions and members
    Sreops->>+Github : Push source terraform into repo on branch automation
```