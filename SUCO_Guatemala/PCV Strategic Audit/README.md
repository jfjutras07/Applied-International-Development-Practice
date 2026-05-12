# Strategic Audit of the PCV Program in Guatemala  
### Integrated Program Reconstruction, Organizational Intelligence & Exploratory Machine Learning  
**Multi-Level Analysis of Mandates, Projects, and Organizational Performance in a Low-Data Development Context**

---

The objective of this project is to conduct a strategic audit of the PCV program in Guatemala using a reconstruction-based analytical framework applied to fragmented program data.

The analysis integrates:

- **Program Reconstruction:** Harmonization of mandates, projects, deliverables, partners, and cooperants into a unified analytical structure  
- **Proxy-Based Indicators:** Construction of composite indices capturing quality, adoption, transformation, results, context, and risk  
- **Operational Structure Analysis:** Mapping of mandates, partners, and capacity families to understand execution concentration  
- **Exploratory Machine Learning:** Unsupervised clustering and feature importance modeling to detect latent organizational patterns  
- **System-Level Interpretation:** Identification of structural constraints, execution logic, and program-wide behavioral dynamics  

This project is not designed for predictive modeling or causal inference, but for **strategic interpretation and organizational sense-making in a low-data environment**.

---

## Data Architecture & Program Reconstruction

- **Multi-Table Integration:** Consolidation of mandates, projects, deliverables, partners, and cooperants into a single analytical ecosystem  
- **Project-Centric Dataset:** Reconstructed dataset of 32 projects with standardized structural and performance variables  
- **Standardization Process:**
  - Normalization of project types and capacity families  
  - Alignment of heterogeneous administrative sources  
  - Construction of unified project-level analytical frame  

### Feature Engineering

- **Operational Intensity Variables:**
  - Project duration (months)
  - Production density
  - Average complexity score  

- **Structural Classification System:**
  - Project type (intervention format: policy, tools, training, analysis, revision)  
  - Strategic classification (operational intensity: light, complex, specialized, high-volume)  
  - Functional classification (internal vs external projects)
  
  <img width="1360" height="647" alt="image" src="https://github.com/user-attachments/assets/0defa806-2401-4e39-9139-554031886614" />

- **Composite Indices:**
  - Quality (calidad)
  - Adoption (i_adopcion)
  - Transformation (i_transformation)
  - Results (i_resultados)
  - Context (i_contexto)
  - Risk (i_riesgo)

<img width="1354" height="532" alt="image" src="https://github.com/user-attachments/assets/c461332d-c239-455b-86d3-471d2acad86a" />

---

## Exploratory Program Architecture Analysis

### Program Scale & Structure

- 32 projects, 124 deliverables  
- 11 mandates, 10 cooperants, 6 partner organizations  
- High operational density with concentrated execution hubs  

---

### Dual Program Logic

- **Transversal System Layer**
  - Project management systems  
  - Organizational development functions  
  - Standardized tools and methodologies  

- **Thematic Intervention Layer**
  - Gender equality  
  - Agroecology  
  - Environment  
  - Communication  
  - Solidarity economy
 
<img width="1017" height="691" alt="image" src="https://github.com/user-attachments/assets/f7634822-525a-45f9-a775-44eb19840854" />

---

## Exploratory Machine Learning & Pattern Detection

### Unsupervised Clustering Results

- Two main latent project archetypes identified:
  - Structured / systemic interventions  
  - Operational / high-throughput interventions
 
<img width="1068" height="626" alt="image" src="https://github.com/user-attachments/assets/8a860ae1-35ca-40a0-90fc-0fc5bd62e467" />
 

- Cluster separation is moderate, indicating:
  - Hybrid project architecture  
  - Overlapping implementation logics  
  - Weak categorical rigidity in program design  

---

### Key Pattern Findings

- Project behavior is driven more by **implementation dynamics** than formal classification  
- Longer projects tend to align with stronger **transformation and adoption outcomes**  
- High production density projects are more execution-oriented but less transformative  

---

## System-Level Dependency Structure

Exploratory Random Forest modeling reveals a non-symmetric dependency system:

- **Context & Adoption → upstream drivers**  
- **Transformation → bridging mechanism**  
- **Results → downstream outcome layer**  
- **Quality & Risk → systemic modulators**  

Key relationships:

- Adoption strongly linked to transformation  
- Transformation strongly linked to results  
- Context consistently acts as a constraint across all dimensions

<img width="797" height="218" alt="image" src="https://github.com/user-attachments/assets/b6959aeb-aa22-4496-9f23-2d99b5ac517e" />

---

## Strategic Insights

### Organizational Structure

- Strong concentration of execution in a limited number of mandates  
- Key operational dependency on SEA and Project Management structures  
- Uneven distribution of implementation responsibility across partners  

---

### Program Behavior

- Internal performance projects dominate the portfolio  
- External beneficiary projects are longer and more complex but not necessarily more effective  
- Incidence-oriented projects are fewer and structurally more complex  

---

### System Constraints

- Consistently low organizational absorption capacity (context)  
- Moderate transformation capacity across the system  
- Stable but structurally constrained performance environment  

---

## Methodological Contributions

- Demonstrates feasibility of reconstruction-based analytics in low-data environments  
- Shows how proxy indicators can support structured organizational interpretation  
- Combines:
  - Descriptive analytics  
  - Unsupervised learning  
  - Interpretable ML models  

---

## Limitations

- Small sample size (n = 32 projects)  
- Proxy-based indicators (no ground truth validation)  
- Exploratory ML only (no causal inference)  
- Moderate cluster separability  

---

## Strategic Recommendations

- Strengthen transversal systems (Project Management, SEA)  
- Improve organizational absorption capacity  
- Reduce dependency on a small number of execution actors  
- Standardize methodologies and implementation tools  
- Shift evaluation focus from categories to implementation dynamics  

---

## Conclusion

This project demonstrates how fragmented program data can be transformed into a structured analytical system capable of generating strategic insights.

Rather than relying on traditional statistical inference, the framework builds an **interpretive intelligence layer** combining reconstruction, composite indicators, and exploratory machine learning.

It provides a scalable approach for analyzing complex development programs in contexts where data is incomplete, heterogeneous, and operationally constrained.
