
**Note:**
- Make a difference between concepts and grouped disciplines (physic of life)
- Color (define classes) the disciples, groupes, concepts
- subgraphs pg 186
- Edge color
- Node color
- Subgraph color
```mermaid
%%{init:{"theme":"neutral", "themeVariables": { "primaryColor":"#cb9edb", "secondaryColor":"#ddc0e8", "tertiaryColor":"#edddf3", "mainBkg":"white", "nodeBorder":"#4E4E4E", "clusterBkg":"#fff", "clusterBorder":"#4E4E4E", "titleColor":"#4E4E4E", "lineColor":"#4E4E4E", "edgeLabelBackground":"#fff" }}}%%
flowchart TB
   classDef ConceptColorA fill:#4E4E4E, stroke:#4E4E4E, stroke-width:4px,color:#fff
   classDef ConceptColorB fill:#66CC00, stroke-width:4px,color:#4E4E4E

   subgraph A44[Application Layer]
   A38[Physics of self-organisation] & A39[Statical Physics of self-replication] & A40[Programmable Matter]
   end

   subgraph A53[Metrics]
    A41[Metric1] --- A42[Metric2] --- A43[Metric3]
   end

    A1[von Neumann Universal Constructor]:::ConceptColorA --> A2[Physics of Information] & A3[Physics of Life] & A4[Potential Fields]
    A2[Physics of Information] --> A5[Physics of Computation]
    A3 --> A9[Synthetic Biology] & A10[Living Matter]
    A1 --> A6[Principle of stationary action] & A7[Principle of least constraint]
    A1 --> A13[Thermodynamics]
    A6 & A7 --> A11[Weak & Strong Emergence] & A12[Energy Landscapes]
    A13 --> A12
    A13 --> A14[Stochastic Thermodynamics]
    A14 --> A15[Thermodynamical Costs of Computation] & A16[Thermodynamical Efficiency]
    A17[Physical Limits of Computation] --> A16 & A15
    A17 --> A18[Landauer's Limit]
    A17 ==> A19[Computational Efficiency]
    A5 --> A17
    A17 ==> A20[Computing Science] & A21 & A22
    A20 --> A21[Chemical Computing]
    A20 --> A22[Biological Computing]
    A23[Moore's Law] --> A25[Ultimate Cell size Limit] --> A24[What are the ultimate lowest physical limit - Wolpert, Seth Lloyd?]
    A17 --> A26(Avogadro's Limit/Number?)
    A17 --> A25
    A11 --> A27[Cellular Automata]
    A17 -.-> A28[Kolmogorov Complexity]
    A28 & A20 --> A29[Algorithmic Information Content]
    A20 --> A29[Self-delimiting program / Halting Problem?]
    A24 ---> A30[Rate of Change] --- A31[Chemical Reaction Speed] & A32[Entropy Speed] & A33[Speed of Computation] & A34[Speed of Cell-processes] & A35[Speed of Thoughts]
    A10 --- A36[Computational Matter] --- A37[Natural Computing] --> A9
    A37 -.-> A21 & A22

    click A21 "http://www.google.com" "Learn more on chemical computing" _top

    class A4,A7,A12 ConceptColorB
    linkStyle 10 stroke:#66CC00, stroke-width:6px, color:#66CC00

```

# Universal Constructor Categories
Note:
- Definition of "Universal Constructor
- Is "self-replication a feature of Universal Constructor?"
- UC categories or self-replication?
-
```mermaid
%%{init:{"theme":"neutral", "themeVariables": { "primaryColor":"#cb9edb", "secondaryColor":"#ddc0e8", "tertiaryColor":"#edddf3", "mainBkg":"white", "nodeBorder":"#4E4E4E", "clusterBkg":"#fff", "clusterBorder":"#4E4E4E", "titleColor":"#4E4E4E", "lineColor":"#4E4E4E", "edgeLabelBackground":"#fff" }}}%%

flowchart TB
   classDef ConceptColorA fill:#4E4E4E, stroke:#4E4E4E, stroke-width:4px,color:#fff
   classDef ConceptColorB fill:#66CC00, stroke-width:4px,color:#4E4E4E

    A1[von Neumann Universal Constructor Features]:::ConceptColorA --> A2[Self-replication] & A3[Self-assembling] & A4[Feat 3]

    click A1 "http://www.google.com" "Learn more on chemical computing" _top


```

#

```mermaid
%%{init:{"theme":"neutral", "themeVariables": { "primaryColor":"#cb9edb", "secondaryColor":"#ddc0e8", "tertiaryColor":"#edddf3", "mainBkg":"white", "nodeBorder":"#4E4E4E", "clusterBkg":"#fff", "clusterBorder":"#4E4E4E", "titleColor":"#4E4E4E", "lineColor":"#4E4E4E", "edgeLabelBackground":"#fff" }}}%%

flowchart TB
   classDef ConceptColorA fill:#4E4E4E, stroke:#4E4E4E, stroke-width:4px,color:#fff
   classDef ConceptColorB fill:#66CC00, stroke-width:4px,color:#4E4E4E

    A1[von Neumann Universal Constructor Categories]:::ConceptColorA --> A2[Cat 1] & A3[Cat2] & A4[Cat3]

    click A1 "http://www.google.com" "Learn more on chemical computing" _top


```
