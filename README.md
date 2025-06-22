```diff
- Please find above an UPDATED extended version of the paper including all missing proofs and the empirical results.
```
## Environment requirement

* JDK 1.8
* IDE: IDEA 
* Maven

## Data

* Statistics of Oxford-ISG & BioPortal (Min:Minimum, Max:Maximum, Med:Medium, 90 Ptl: 90th Percentile):


<div align="center">
<table class="tg">
<thead>
  <tr>
    <th class="tg-7btt" colspan="2">Oxford</th>
    <th class="tg-7btt">Min</th>
    <th class="tg-7btt">Max</th>
    <th class="tg-7btt">Med</th>
    <th class="tg-7btt">Mean</th>
    <th class="tg-7btt">90Ptl</th>
    <th class="tg-7btt">%</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-c3ow" rowspan="3">I</td>
    <td class="tg-c3ow">|N<sub>C</sub>|</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">1582</td>
    <td class="tg-c3ow">86</td>
    <td class="tg-c3ow">191</td>
    <td class="tg-c3ow">545</td>
    <td class="tg-c3ow">n/a</td>
  </tr>
  <tr>
    <td class="tg-c3ow">|N<sub>R</sub>|</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">332</td>
    <td class="tg-c3ow">10</td>
    <td class="tg-c3ow">29</td>
    <td class="tg-c3ow">80</td>
    <td class="tg-c3ow">n/a</td>
  </tr>
  <tr>
    <td class="tg-c3ow">|Onto|</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">990</td>
    <td class="tg-c3ow">162</td>
    <td class="tg-c3ow">262</td>
    <td class="tg-c3ow">658</td>
    <td class="tg-c3ow">82.20</td>
  </tr>
  <tr>
    <td class="tg-c3ow" rowspan="3">II</td>
    <td class="tg-c3ow">|N<sub>C</sub>|</td>
    <td class="tg-c3ow">200</td>
    <td class="tg-c3ow">5877</td>
    <td class="tg-c3ow">1665</td>
    <td class="tg-c3ow">1769</td>
    <td class="tg-c3ow">2801</td>
    <td class="tg-c3ow">n/a</td>
  </tr>
  <tr>
    <td class="tg-c3ow">|N<sub>R</sub>|</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">887</td>
    <td class="tg-c3ow">11</td>
    <td class="tg-c3ow">34</td>
    <td class="tg-c3ow">61</td>
    <td class="tg-c3ow">n/a</td>
  </tr>
  <tr>
    <td class="tg-c3ow">|Onto|</td>
    <td class="tg-c3ow">1008</td>
    <td class="tg-c3ow">4976</td>
    <td class="tg-c3ow">2282</td>
    <td class="tg-c3ow">2416</td>
    <td class="tg-c3ow">3937</td>
    <td class="tg-c3ow">89.70</td>
  </tr>
  <tr>
    <td class="tg-c3ow" rowspan="3">III</td>
    <td class="tg-c3ow">|N<sub>C</sub>|</td>
    <td class="tg-c3ow">1162</td>
    <td class="tg-c3ow">9809</td>
    <td class="tg-c3ow">4042</td>
    <td class="tg-c3ow">5067</td>
    <td class="tg-c3ow">8758</td>
    <td class="tg-c3ow">n/a</td>
  </tr>
  <tr>
    <td class="tg-c3ow">|N<sub>R</sub>|</td>
    <td class="tg-c3ow">1</td>
    <td class="tg-c3ow">158</td>
    <td class="tg-c3ow">4</td>
    <td class="tg-c3ow">23</td>
    <td class="tg-c3ow">158</td>
    <td class="tg-c3ow">n/a</td>
  </tr>
  <tr>
    <td class="tg-c3ow">|Onto|</td>
    <td class="tg-c3ow">5112</td>
    <td class="tg-c3ow">9783</td>
    <td class="tg-c3ow">7277</td>
    <td class="tg-c3ow">7195</td>
    <td class="tg-c3ow">9179</td>
    <td class="tg-c3ow">94.45</td>
  </tr>
  <tr>
    <td class="tg-7btt" colspan="2">BioPortal</td>
    <td class="tg-7btt">Min</td>
    <td class="tg-7btt">Max</td>
    <td class="tg-7btt">Med</td>
    <td class="tg-7btt">Mean</td>
    <td class="tg-7btt">90Ptl</td>
    <td class="tg-7btt">%</td>
  </tr>
  <tr>
    <td class="tg-c3ow" rowspan="3">I</td>
    <td class="tg-c3ow">|N<sub>C</sub>|</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">784</td>
    <td class="tg-c3ow">127</td>
    <td class="tg-c3ow">192</td>
    <td class="tg-c3ow">214</td>
    <td class="tg-c3ow">n/a</td>
  </tr>
  <tr>
    <td class="tg-c3ow">|N<sub>R</sub>|</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">122</td>
    <td class="tg-c3ow">5</td>
    <td class="tg-c3ow">15</td>
    <td class="tg-c3ow">17</td>
    <td class="tg-c3ow">n/a</td>
  </tr>
  <tr>
    <td class="tg-c3ow">|Onto|</td>
    <td class="tg-c3ow">10</td>
    <td class="tg-c3ow">794</td>
    <td class="tg-c3ow">283</td>
    <td class="tg-c3ow">312</td>
    <td class="tg-c3ow">346</td>
    <td class="tg-c3ow">96.89</td>
  </tr>
  <tr>
    <td class="tg-c3ow" rowspan="3">II</td>
    <td class="tg-c3ow">|N<sub>C</sub>|</td>
    <td class="tg-c3ow">5</td>
    <td class="tg-c3ow">4530</td>
    <td class="tg-c3ow">1185</td>
    <td class="tg-c3ow">1459</td>
    <td class="tg-c3ow">1591</td>
    <td class="tg-c3ow">n/a</td>
  </tr>
  <tr>
    <td class="tg-c3ow">|N<sub>R</sub>|</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">131</td>
    <td class="tg-c3ow">12</td>
    <td class="tg-c3ow">30</td>
    <td class="tg-c3ow">33</td>
    <td class="tg-c3ow">n/a</td>
  </tr>
  <tr>
    <td class="tg-c3ow">|Onto|</td>
    <td class="tg-c3ow">1023</td>
    <td class="tg-c3ow">4977</td>
    <td class="tg-c3ow">2401</td>
    <td class="tg-c3ow">2619</td>
    <td class="tg-c3ow">2782</td>
    <td class="tg-c3ow">97.18</td>
  </tr>
  <tr>
    <td class="tg-c3ow" rowspan="3">III</td>
    <td class="tg-c3ow">|N<sub>C</sub>|</td>
    <td class="tg-c3ow">432</td>
    <td class="tg-c3ow">8340</td>
    <td class="tg-c3ow">4363</td>
    <td class="tg-c3ow">4387</td>
    <td class="tg-c3ow">4806</td>
    <td class="tg-c3ow">n/a</td>
  </tr>
  <tr>
    <td class="tg-c3ow">|N<sub>R</sub>|</td>
    <td class="tg-c3ow">0</td>
    <td class="tg-c3ow">135</td>
    <td class="tg-c3ow">17</td>
    <td class="tg-c3ow">30</td>
    <td class="tg-c3ow">34</td>
    <td class="tg-c3ow">n/a</td>
  </tr>
  <tr>
    <td class="tg-c3ow">|Onto|</td>
    <td class="tg-c3ow">5084</td>
    <td class="tg-c3ow">8836</td>
    <td class="tg-c3ow">6934</td>
    <td class="tg-c3ow">6912</td>
    <td class="tg-c3ow">7109</td>
    <td class="tg-c3ow">98.72</td>
  </tr>
</tbody>
</table>
</div>

## Import of this project

* Unzip this project.
* Import it into IDEA.
* Make the src folder as source root.
* Make sure that the jar package under the root folder has been added into project as libriaries.

# Overview of the Forgetting System
  
The Forgetting System Proto is a high-performance method for computing signature-restricted modules of ALCI ontologies. This implementation represents a breakthrough in practical module computation for Web ontologies by addressing the long-standing complexity barriers in this field.

## Core Concepts

The Forgetting System enables the elimination of selected concept and role names from an ontology while preserving all logical entailments over a designated vocabulary. This process, known as "forgetting," allows for the creation of signature-restricted modules that maintain semantic integrity while adhering to strict vocabulary constraints.

## Key Technical Innovations

### Linear Definer Introduction Strategy

The system implements a novel normalization approach that avoids the exponential blow-up observed in existing systems:

- **Controlled Symbol Growth**: Unlike previous approaches that introduce definers exponentially, our system maintains linear growth in the number of auxiliary concept names (definers).
- **Specialized Normal Forms**: The method operates on two purpose-built normal forms:
  - **A-reduced form** for concept name elimination
  - **r-reduced form** for role name elimination
- **Tailored Inference Process**: Our specialized calculus is designed to work efficiently with these normal forms.

### Elimination Calculi

The system employs two independent calculi for eliminating concept and role names:

1. **Concept Name Elimination**: Uses a comprehensive combination rule with 16 distinct inference patterns to handle all possible interactions of concept names.
2. **Role Name Elimination**: Applies a specialized calculus for removing role names while preserving semantic relationships.

## Performance Advantages

The Forgetting System demonstrates significant advantages over previous approaches:

- **Complete Effectiveness**: Achieves 100% success rate across all evaluation tracks in extensive testing.
- **Compact Results**: Produces modules that are often more compact than those generated by syntax-restricted approaches.
- **Efficient Computation**: Performs on par with or better than subset modularization methods in terms of computation time.
- **Reduced Memory Consumption**: Requires 20-40% less memory than existing forgetting methods.



# Run of the Forgetting System

## Basic Usage

To run the forgetting method, go to **/src/forgetting/Forgetter.class** and call the method:

java

```java
public Set<OWLAxiom> ForgettingAPI(Set<OWLObjectProperty> roles, Set<OWLClass> concepts, OWLOntology onto)
```

### Parameters:

- `roles`: A set of role names (OWLObjectProperty) to be forgotten
- `concepts`: A set of concept names (OWLClass) to be forgotten
- `onto`: The input ALCI-Ontology from which the specified names will be forgotten

### Return Value:

- A set of OWLAxioms representing the signature-restricted module of the ontology `onto` with respect to the remaining signature
