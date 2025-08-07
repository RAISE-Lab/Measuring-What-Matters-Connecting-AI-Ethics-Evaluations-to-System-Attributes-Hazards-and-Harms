# Measuring-What-Matters-Connecting-AI-Ethics-Evaluations-to-System-Attributes-Hazards-and-Harms
Over the past decade, an ecosystem of measures has emerged to evaluate the social and ethical implications of AI systems, largely shaped by high-level ethics principles. These measures are developed and used in fragmented ways, without adequate attention to how they are situated in AI systems. In this paper, we examine how existing measures used in the computing literature map to AI system components, attributes, hazards, and harms. Our analysis draws on a scoping review resulting in nearly 800 measures corresponding to 11 AI ethics principles. We find that most measures focus on four principles— fairness, transparency, privacy, and trust— and primarily assess model or output system components. Few measures account for interactions across system elements, and only a narrow set of hazards is typically considered for each harm type. Many measures are disconnected from where harm is experienced and lack guidance for setting meaningful thresholds. These patterns reveal how current evaluation practices remain fragmented, measuring in pieces rather than capturing how harms emerge across systems. Framing measures with respect to system attributes, hazards, and harms can strengthen regulatory oversight, support actionable practices in industry, and ground future research in systems-level understanding.

# Dataset Information and Interactive Visualization Link

Currently, this work is on Version 2.0 of the publicly shared dataset and corresponding visualization. It is named "RAI_Measures_Dataset_Version_2.0.xlsx". The dataset is in a Microsoft Excel (.xslx) format. Note that it is not recommended to open the file in a .csv format due to the increased likelihood of corrupted characters and file formatting. Please read the below sections for more information on the dataset.

## Using the Dataset
The spreadsheet includes user guidance stages grouping eighteen columns. These user guidance stages intentionally divide and describe the data columns among similarities that they share. The interactive Sunburst visualization can be found here: **https://RAI-Measures.onrender.com**. 

**Target Output (Columns A and B)**: The resulting measures collected in this dataset.
  
  1. Measure
  2. Measurement Process
     
**Entry Points (Columns C and D)**: The primary features in narrowing down potential measures for an algorithmic system.
  
  3. Principle
  4. ML System Component 

**Connections to Harm (Columns E - H)**: Investigating the identification and relations to harm, hazards, and attributes.
  
  5. Primary Harm
  6. Secondary Harm
  7. Hazard
  8. Attribute

**Measurement Properties (Columns I - K)**: The standard(s) per which each measure uses in its evaluation.
  
  9. Criterion Name 
  10. Criterion Description 
  11. Type of Assessment

**Algorithmic System Characteristics (Columns L - O)**: Additional features that a user can consider when narrowing down measures to use.
  
  12. Application Area
  13. Purpose of ML System 
  14. Type of Data
  15. Algorithm Type

**Publication Metadata (Columns P - R)**: Details further documentation into each source that was extracted to collect each feature and measure.
  
  16. Title (Note its hyperlink to the article itself)
  17. Year
  18. Key Contributions 

## Using the Interactive Visualization
This dataset has a corresponding visualization that can be dynamically interacted with. It can be found as the "Interactive_Visualization_Link_Version_2.0.md" file in this repository.
