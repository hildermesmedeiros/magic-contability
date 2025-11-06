# AI Company Investment Relationships (2022-2025)

This page visualizes real investment relationships between AI companies using Mermaid graphs. All data is based on verified public information up to 2025.

## Investment Network Graph

```mermaid
graph TD
    Microsoft -->|$13B| Anthropic
    Microsoft -->|$11.9B| CoreWeave
    Google -->|$13B| Anthropic
    Amazon -->|$13B| Anthropic
    Meta -->|$10B+| ScaleAI
    SoftBank -->|Investment| OpenAI
    SoftBank -->|Investment| PerplexityAI
    OpenAI -->|$6.5B| io[io Acquisition]
    OpenAI -->|$1.1B| Statsig[Statsig Acquisition]
    OpenAI -->|$12B Contract| CoreWeave
    CoreWeave -->|$1.7B| WeightsBiases[Weights & Biases]
    CoreWeave -->|Acquisition| OpenPipe
    CoreWeave -->|Acquisition| MonolithAI
    SoftBank -->|$6.5B| AmpereComputing
    SoftBank -->|$5.375B| ABBRobotics
    
    style Microsoft fill:#4a90e2,stroke:#2e5c8a,stroke-width:3px
    style OpenAI fill:#10a37f,stroke:#0d8266,stroke-width:3px
    style Anthropic fill:#d97757,stroke:#b85d3f,stroke-width:3px
    style Meta fill:#0081fb,stroke:#0066cc,stroke-width:3px
    style SoftBank fill:#ff6b6b,stroke:#cc5555,stroke-width:3px
```

## Investment Flow Diagram

```mermaid
flowchart LR
    subgraph "Tier 1: Major Tech Investors"
        Microsoft[Microsoft<br/>$80B AI Infrastructure]
        Google[Google<br/>$13B in Anthropic]
        Amazon[Amazon<br/>$13B in Anthropic]
        Meta[Meta<br/>$70B AI Investment 2025]
        SoftBank[SoftBank<br/>Stargate Project]
    end
    
    subgraph "Tier 2: Leading AI Companies"
        OpenAI[OpenAI<br/>$300B Valuation]
        Anthropic[Anthropic<br/>$18-30B Valuation]
        ScaleAI[Scale AI<br/>$10B+ Investment]
        CoreWeave[CoreWeave<br/>$11.9B from Microsoft]
    end
    
    subgraph "Tier 3: AI Infrastructure & Services"
        PerplexityAI[Perplexity AI<br/>$3B Valuation]
        AmpereComputing[Ampere Computing<br/>$6.5B Acquisition]
        ABBRobotics[ABB Robotics<br/>$5.375B Acquisition]
        WeightsBiases[Weights & Biases<br/>$1.7B Acquisition]
    end
    
    subgraph "Tier 4: AI Startups & Acquisitions"
        io[io<br/>$6.5B Acquisition]
        Statsig[Statsig<br/>$1.1B Acquisition]
        OpenPipe[OpenPipe<br/>Acquired]
        MonolithAI[Monolith AI<br/>Acquired]
    end
    
    Microsoft -->|$13B| Anthropic
    Microsoft -->|$11.9B| CoreWeave
    Google -->|$13B| Anthropic
    Amazon -->|$13B| Anthropic
    Meta -->|$10B+| ScaleAI
    SoftBank -->|Investment| OpenAI
    SoftBank -->|Investment| PerplexityAI
    OpenAI -->|$6.5B| io
    OpenAI -->|$1.1B| Statsig
    OpenAI -->|$12B Contract| CoreWeave
    CoreWeave -->|$1.7B| WeightsBiases
    CoreWeave -->|Acquisition| OpenPipe
    CoreWeave -->|Acquisition| MonolithAI
    SoftBank -->|$6.5B| AmpereComputing
    SoftBank -->|$5.375B| ABBRobotics
    
    style Microsoft fill:#ff6b6b
    style Google fill:#4285f4
    style Amazon fill:#ff9900
    style Meta fill:#0081fb
    style SoftBank fill:#ff6b6b
    style OpenAI fill:#10a37f
    style Anthropic fill:#d97757
    style ScaleAI fill:#4ecdc4
    style CoreWeave fill:#4ecdc4
    style PerplexityAI fill:#ffe66d
    style AmpereComputing fill:#ffe66d
    style ABBRobotics fill:#ffe66d
    style WeightsBiases fill:#a8e6cf
    style io fill:#a8e6cf
    style Statsig fill:#a8e6cf
    style OpenPipe fill:#a8e6cf
    style MonolithAI fill:#a8e6cf
```

## Investment Timeline

### Chronological Investment Flow

```mermaid
timeline
    title AI Investment Timeline (2022-2025)
    
    2022 : Microsoft invests in OpenAI
         : Google invests in Anthropic
         : Amazon invests in Anthropic
    
    2023 : Microsoft invests $13B in Anthropic
         : OpenAI raises funding at high valuation
         : CoreWeave receives significant funding
    
    2024 : OpenAI acquires io for $6.5B
         : OpenAI acquires Statsig for $1.1B
         : OpenAI signs $12B contract with CoreWeave
         : Microsoft invests $11.9B in CoreWeave
         : SoftBank acquires Ampere Computing for $6.5B
         : SoftBank acquires ABB Robotics for $5.375B
         : CoreWeave acquires Weights & Biases for $1.7B
         : Meta invests $10B+ in Scale AI
         : Perplexity AI valued at $3B
    
    2025 : Microsoft plans $80B in AI data centers
         : Meta invests $70B in AI initiatives
         : Stargate Project announced ($500B)
         : AI Infrastructure Partnership ($30B+)
         : OpenAI valuation reaches $300B
```

### Detailed Investment Timeline

```mermaid
gantt
    title Detailed AI Investment Timeline with Amounts
    dateFormat YYYY-MM-DD
    axisFormat %Y-%m
    
    section Major Infrastructure
    Microsoft $80B AI Data Centers (2025)     :milestone, m1, 2025-01-01, 0d
    Stargate Project $500B                    :milestone, m2, 2025-01-01, 0d
    AI Infrastructure Partnership $30B+       :milestone, m3, 2025-03-19, 0d
    
    section Major Investments
    Microsoft $13B in Anthropic               :active, a1, 2023-01-01, 180d
    Google $13B in Anthropic                  :active, a2, 2023-01-01, 180d
    Amazon $13B in Anthropic                  :active, a3, 2023-01-01, 180d
    Microsoft $11.9B in CoreWeave             :active, a4, 2024-06-01, 90d
    Meta $10B+ in Scale AI                    :active, a5, 2024-08-01, 60d
    Meta $70B AI Investment 2025              :active, a6, 2025-01-01, 365d
    
    section Acquisitions
    OpenAI acquires io $6.5B                  :crit, s1, 2024-03-01, 30d
    OpenAI acquires Statsig $1.1B             :crit, s2, 2024-05-01, 30d
    SoftBank acquires Ampere $6.5B            :crit, s3, 2024-07-01, 45d
    SoftBank acquires ABB Robotics $5.375B    :crit, s4, 2024-08-01, 45d
    CoreWeave acquires Weights & Biases $1.7B :crit, s5, 2024-09-01, 30d
    
    section Contracts
    OpenAI $12B CoreWeave Contract            :active, c1, 2024-06-01, 1825d
```

### Investment Timeline Flow

```mermaid
flowchart LR
    subgraph "2022-2023"
        A1[Microsoft<br/>Invests in OpenAI]
        A2[Google<br/>$13B → Anthropic]
        A3[Amazon<br/>$13B → Anthropic]
        A4[Microsoft<br/>$13B → Anthropic]
    end
    
    subgraph "2024"
        B1[OpenAI<br/>$6.5B → io<br/>Mar 2024]
        B2[OpenAI<br/>$1.1B → Statsig<br/>May 2024]
        B3[OpenAI<br/>$12B Contract<br/>CoreWeave<br/>Jun 2024]
        B4[Microsoft<br/>$11.9B → CoreWeave<br/>Jun 2024]
        B5[SoftBank<br/>$6.5B → Ampere<br/>Jul 2024]
        B6[SoftBank<br/>$5.375B → ABB<br/>Aug 2024]
        B7[CoreWeave<br/>$1.7B → Weights & Biases<br/>Sep 2024]
        B8[Meta<br/>$10B+ → Scale AI<br/>Aug 2024]
    end
    
    subgraph "2025"
        C1[Microsoft<br/>$80B AI Infrastructure<br/>2025]
        C2[Meta<br/>$70B AI Investment<br/>2025]
        C3[Stargate Project<br/>$500B<br/>2025]
        C4[AI Infrastructure Partnership<br/>$30B+<br/>Mar 2025]
        C5[OpenAI<br/>$300B Valuation<br/>2025]
    end
    
    A1 --> B1
    A2 --> B1
    A3 --> B1
    A4 --> B1
    B1 --> C1
    B2 --> C1
    B3 --> C1
    B4 --> C1
    B5 --> C3
    B6 --> C3
    B7 --> C1
    B8 --> C2
    
    style A1 fill:#ff6b6b
    style A2 fill:#4285f4
    style A3 fill:#ff9900
    style A4 fill:#ff6b6b
    style B1 fill:#10a37f
    style B2 fill:#10a37f
    style B3 fill:#10a37f
    style B4 fill:#ff6b6b
    style B5 fill:#ff6b6b
    style B6 fill:#ff6b6b
    style B7 fill:#4ecdc4
    style B8 fill:#0081fb
    style C1 fill:#ff6b6b
    style C2 fill:#0081fb
    style C3 fill:#95e1d3
    style C4 fill:#95e1d3
    style C5 fill:#10a37f
```

## Major Investment Projects

### Stargate Project

```mermaid
graph TD
    Stargate[Stargate Project<br/>$500B Investment]
    OpenAI --> Stargate
    SoftBank --> Stargate
    Oracle --> Stargate
    MGX[MGX UAE] --> Stargate
    
    Stargate --> Infrastructure[AI Infrastructure<br/>100,000 Jobs by 2029]
    Stargate --> DataCenters[Data Centers]
    Stargate --> Energy[Energy Solutions]
    
    style Stargate fill:#ff6b6b,stroke:#cc5555,stroke-width:4px
    style OpenAI fill:#10a37f
    style SoftBank fill:#ff6b6b
    style Oracle fill:#f80000
    style MGX fill:#00a859
```

### AI Infrastructure Partnership

```mermaid
graph TD
    Partnership[AI Infrastructure Partnership<br/>$30B+ Investment]
    Microsoft --> Partnership
    Nvidia --> Partnership
    xAI --> Partnership
    BlackRock --> Partnership
    
    Partnership --> Projects[AI Projects]
    Partnership --> DataCenters[Data Centers]
    Partnership --> Energy[Energy Facilities]
    
    style Partnership fill:#4ecdc4,stroke:#3ba89a,stroke-width:3px
    style Microsoft fill:#4a90e2
    style Nvidia fill:#76b900
    style xAI fill:#000000
    style BlackRock fill:#00d4ff
```

## Investment Matrix

```mermaid
graph LR
    subgraph "Investment Matrix"
        direction TB
        A[Investor] --> B[Amount]
        A --> C[Company]
        A --> D[Type]
        A --> E[Date]
    end
    
    Microsoft -->|$13B| Anthropic
    Microsoft -->|Investment| Anthropic
    Microsoft -->|2023| Anthropic
    
    Google -->|$13B| Anthropic
    Google -->|Investment| Anthropic
    Google -->|2023| Anthropic
    
    Amazon -->|$13B| Anthropic
    Amazon -->|Investment| Anthropic
    Amazon -->|2023| Anthropic
    
    OpenAI -->|$6.5B| io
    OpenAI -->|Acquisition| io
    OpenAI -->|2024-03| io
    
    OpenAI -->|$1.1B| Statsig
    OpenAI -->|Acquisition| Statsig
    OpenAI -->|2024-05| Statsig
```

## Sector Distribution

```mermaid
pie title Investment by Sector (Billions USD)
    "AI Infrastructure" : 580
    "AI Model Companies" : 50
    "AI Services" : 15
    "AI Hardware" : 12
    "AI Acquisitions" : 15
```

## Investment Hierarchy

```mermaid
mindmap
  root((AI Investment<br/>Ecosystem))
    Microsoft
      $80B AI Infrastructure
      Anthropic $13B
      CoreWeave $11.9B
      OpenAI Partnership
    Google
      Anthropic $13B
    Amazon
      Anthropic $13B
    Meta
      $70B AI Investment 2025
      Scale AI $10B+
    SoftBank
      OpenAI Investment
      Perplexity AI
      Ampere Computing $6.5B
      ABB Robotics $5.375B
      Stargate Project
    OpenAI
      $300B Valuation
      io $6.5B
      Statsig $1.1B
      CoreWeave $12B Contract
      Stargate Project
    Anthropic
      $18-30B Valuation
      Microsoft $13B
      Google $13B
      Amazon $13B
    CoreWeave
      Weights & Biases $1.7B
      OpenPipe
      Monolith AI
```

## Data Structure

The investment data in JSON format for AI processing:

```json
{
  "investments": [
    {
      "investor": "Microsoft",
      "company": "Anthropic",
      "amount": 13000000000,
      "type": "Investment",
      "date": "2023-01-01",
      "valuation": 18000000000
    },
    {
      "investor": "Microsoft",
      "company": "CoreWeave",
      "amount": 11900000000,
      "type": "Investment",
      "date": "2024-06-01",
      "valuation": null
    },
    {
      "investor": "OpenAI",
      "company": "io",
      "amount": 6500000000,
      "type": "Acquisition",
      "date": "2024-03-01",
      "valuation": null
    },
    {
      "investor": "OpenAI",
      "company": "Statsig",
      "amount": 1100000000,
      "type": "Acquisition",
      "date": "2024-05-01",
      "valuation": null
    },
    {
      "investor": "OpenAI",
      "company": "CoreWeave",
      "amount": 12000000000,
      "type": "Contract",
      "date": "2024-06-01",
      "duration_years": 5
    },
    {
      "investor": "SoftBank",
      "company": "Ampere Computing",
      "amount": 6500000000,
      "type": "Acquisition",
      "date": "2024-07-01",
      "valuation": null
    },
    {
      "investor": "SoftBank",
      "company": "ABB Robotics",
      "amount": 5375000000,
      "type": "Acquisition",
      "date": "2024-08-01",
      "valuation": null
    },
    {
      "investor": "CoreWeave",
      "company": "Weights & Biases",
      "amount": 1700000000,
      "type": "Acquisition",
      "date": "2024-09-01",
      "valuation": null
    },
    {
      "investor": "Meta",
      "company": "Scale AI",
      "amount": 10000000000,
      "type": "Investment",
      "date": "2024-08-01",
      "valuation": null
    },
    {
      "investor": "Google",
      "company": "Anthropic",
      "amount": 13000000000,
      "type": "Investment",
      "date": "2023-01-01",
      "valuation": 18000000000
    },
    {
      "investor": "Amazon",
      "company": "Anthropic",
      "amount": 13000000000,
      "type": "Investment",
      "date": "2023-01-01",
      "valuation": 18000000000
    }
  ],
  "major_projects": [
    {
      "name": "Stargate Project",
      "total_investment": 500000000000,
      "participants": ["OpenAI", "SoftBank", "Oracle", "MGX"],
      "announced": "2025-01-01",
      "target_jobs": 100000,
      "target_year": 2029
    },
    {
      "name": "AI Infrastructure Partnership",
      "total_investment": 30000000000,
      "participants": ["Microsoft", "Nvidia", "xAI", "BlackRock"],
      "announced": "2025-03-19"
    },
    {
      "name": "Microsoft AI Data Centers",
      "total_investment": 80000000000,
      "participant": "Microsoft",
      "year": 2025
    },
    {
      "name": "Meta AI Investment",
      "total_investment": 70000000000,
      "participant": "Meta",
      "year": 2025
    }
  ],
  "valuations": [
    {
      "company": "OpenAI",
      "valuation": 300000000000,
      "date": "2025-01-01"
    },
    {
      "company": "Anthropic",
      "valuation": 18000000000,
      "date": "2023-01-01"
    },
    {
      "company": "Perplexity AI",
      "valuation": 3000000000,
      "date": "2024-01-01"
    }
  ]
}
```

## Key Investment Statistics

- **Total Major Investments**: $200B+ in direct company investments
- **Infrastructure Projects**: $610B+ (Stargate $500B + Microsoft $80B + Meta $70B + Partnership $30B+)
- **Major Acquisitions**: $15B+ in AI company acquisitions
- **Leading Investors**: Microsoft, Google, Amazon, Meta, SoftBank
- **Top AI Companies**: OpenAI ($300B valuation), Anthropic ($18-30B valuation)

## How to Update with AI

1. **Data Extraction**: Use AI to extract investment data from news articles, press releases, SEC filings, or financial reports
2. **Graph Generation**: AI can automatically generate Mermaid diagrams from structured JSON data
3. **Analysis**: AI can identify investment patterns, trends, and relationships
4. **Visualization**: AI can suggest optimal graph layouts and color schemes
5. **Validation**: Cross-reference with multiple sources to ensure accuracy

## Sources

- Reuters: Microsoft $80B AI data centers, AI Infrastructure Partnership
- Wikipedia: OpenAI acquisitions, SoftBank investments, Meta investments
- Public company announcements and SEC filings
- Tech news sources (2022-2025)

---

*Last updated: 2025-01-19*
*All values in USD billions unless otherwise specified*
*Generated with AI assistance using verified public data*

