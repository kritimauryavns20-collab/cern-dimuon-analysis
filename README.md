README.md
# CERN Dimuon Data Analysis

## Introduction   
This project analyzes dimuon event data obtained from CERN Open Data. A dimuon event refers to a particle collision in which two muons are detected. Muons are elementary particles similar to electrons but with greater mass.

These muons are produced during high-energy collisions in the Large Hadron Collider (LHC). Each event represents a single collision, and when two muons are identified, it is classified as a dimuon event.

## Dataset
This project analyzes dimuon event data obtained from CERN Open Data. A dimuon event refers to a particle collision in which two muons are detected. Muons are elementary particles similar to electrons but with greater mass.

These muons are produced during high-energy collisions in the Large Hadron Collider (LHC). Each event represents a single collision, and when two muons are identified, it is classified as a dimuon event.

## Analysis 1: Invariant Mass Distribution
The histogram represents the distribution of invariant mass values of dimuon events.

A dimuon event refers to a particle collision in which two muons are detected. Muons are elementary particles similar to electrons but with greater mass, and they are commonly produced in high-energy collisions at CERN’s Large Hadron Collider. Each recorded event corresponds to a single collision where two muons are identified.

For each event, properties such as the energy and momentum of the muons are measured. Using these values, the invariant mass (M) of the muon pair is calculated. This quantity represents the effective combined mass of the two muons and is a key parameter in particle physics analysis.

### Observation

From the histogram, we observe a strong peak around 90 GeV. Most of the data is concentrated between approximately 80 GeV and 100 GeV, with fewer events at lower (below 50 GeV) and higher mass values (above 110 GeV).

### Interpretation

This peak closely matches the known mass of the Z boson (~91 GeV), suggesting that a large number of these events are produced from Z boson decays into muon pairs.

The concentration of values around this range indicates the presence of a dominant physical process. Overall, the histogram shows that the dataset is not randomly distributed but reflects underlying physical laws governing particle interactions and decay processes.

## Analysis 2: Muon Energy Comparison
This scatter plot shows the relationship between the energies of the two muons (E1 and E2) detected in each dimuon event.

Each point on the graph represents a single event, where the x-axis corresponds to the energy of the first muon (E1) and the y-axis corresponds to the energy of the second muon (E2).

### Observation

The points are widely scattered across the graph, with most values concentrated at lower energy ranges. There is no clear pattern or straight-line relationship between E1 and E2. A few points appear at higher energy values, but they are relatively rare.

### Interpretation

This indicates that there is no strong correlation between the energies of the two muons. The energy of one muon does not directly determine the energy of the other. The distribution also shows that most dimuon events occur at lower energy values, while high-energy events are less frequent.

## Analysis 3: Transverse Momentum Distribution
This histogram compares the transverse momentum (pt) of the two muons in each dimuon event. Transverse momentum represents the motion of a particle perpendicular to the beam direction.

### Observation

The majority of the values for both muons are concentrated between approximately 20 GeV and 60 GeV. The distributions of Muon 1 and Muon 2 are very similar and largely overlap. Only a few events have higher momentum values above 80 GeV.

### Interpretation

This indicates that most muons are produced with moderate transverse momentum, and high-momentum events are relatively rare. The similarity between the two distributions suggests that both muons behave consistently and have comparable momentum characteristics.

## Conclusion
In this project, we analyzed dimuon event data obtained from CERN Open Data. Using visualization techniques, we explored the distribution and relationships within the dataset.

The invariant mass histogram showed a strong peak around 90 GeV, indicating that most dimuon events occur within a specific mass range. The scatter plot comparing the energies of the two muons revealed that there is no strong correlation between them. The transverse momentum distribution showed that most muons have moderate momentum, with fewer high-momentum events.

Overall, this project demonstrates how data analysis and visualization can help identify patterns and extract meaningful insights from scientific datasets.
