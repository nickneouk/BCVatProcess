```mermaid
---
title: VAT Setup Process in Business Central
---
flowchart TD
    subgraph VATSetup["VAT Setup"]
        A[Start VAT Setup] --> B[Define VAT Business Posting Groups]
        B --> C[Define VAT Product Posting Groups]
        C --> D[Configure VAT Posting Setup]
        D --> E[Set Up VAT Statement]
        E --> F[Run VAT Settlement]
        F --> G[Submit VAT Report]
    end

    G --> H[End Process]
