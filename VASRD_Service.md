BID 0001AQ Discovery Reports

-December 2018, 2021

--Exhibit 3 30: VASRD Main Processes

```mermaid
sequenceDiagram
    participant R as VBMS-R
    participant V as VASRD
    R->>V: Search for Evaluation Builder
    activate V
    V->>R: Evaluation Builder Results
    deactivate V
    activate R
    R->>V: VASRD Enter Rating Period
    deactivate R
    activate V
    V->>R: Ratings Return Rating Schedule UI
    deactivate V
    activate R
    R->>V: VASRD Submit Execution Input
    deactivate R
    activate V
    V->>R: Ratings Return Rule Execution Results
    deactivate V
    activate R
```
