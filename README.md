# Pectoral Muscle Removal from Mammograms
<figure>
  <img src="https://github.com/gsunit/Pectoral-Muscle-Removal-From-Mammograms/blob/master/algorithm-screenshot.png" alt="algorithm-screenshot"/>
  <figcaption>Screenshot of the image processing algorithm from the Jupyter Notebook</figcaption>
</figure>

## Glossary
### Mammograms
A mammogram is an X-ray picture of the breast. Doctors use a mammogram to look for early signs of breast cancer.

## Algorithm
```mermaid
graph LR

A(Start)

A --> B[Look for an item]

B --> C{Did you find it?}
C -->|Yes| D(Stop looking)
C -->|No| E{Do you need it?}
E -->|Yes| B
E -->|No| D
