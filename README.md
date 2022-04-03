# Medicaid-Pharmacy-Pricing-Analysis

## Overview


## Languages & Tools:

- Python

- Machine Learning

- Azure

- Tableau

- Neo4j

- Cypher

## Dataset:

These datasets are provided by the US Medicaid's Pharmacy Pricing: 

## Analysis

### 1/ Creating sample tables & relationships

In this step, I created different sample nodes on Neo4j using the key variables retrieved from the similar dataset on US Medicaid website. This is to show how to establish nodes, relationships and joins between nodes for further insights.

```
CREATE (product1: Product {product_group: "13", ingredient: "ACETAMINOPHEN; CODEINE PHOSPHATE", strength: "300MG;15MG", mdr_unit_type: "TAB", arated: "Yes", year: "2022", month: "3"})
CREATE (product2: Product {product_group: "14", ingredient: "ACETAMINOPHEN; OXYCODONE HYDROCHLORIDE", strength: "325MG;5MG", mdr_unit_type: "TAB", arated: "Yes", year: "2022", month: "3"})
CREATE (product3: Product {product_group: "33", ingredient: " ACETAZOLAMIDE", strength: "125MG", mdr_unit_type: "TAB", arated: "Yes", year: "2022", month: "3"})
CREATE (product4: Product {product_group: "43", ingredient: " ACYCLOVIR", strength: "200MG", mdr_unit_type: "TAB", arated: "Yes", year: "2022", month: "3"})
CREATE (product5: Product {product_group: "53", ingredient: "ALBUTEROL SULFATE", strength: "2MG", mdr_unit_type: "TAB", arated: "Yes", year: "2022", month: "3"})
CREATE (product6: Product {product_group: "58", ingredient: "ALLOPURINOL", strength: "100MG", mdr_unit_type: "TAB", arated: "Yes", year: "12", month: "3"})
CREATE (product7: Product {product_group: "60", ingredient: "ALPRAZOLAM", strength: "0.25MG", mdr_unit_type: "TAB", arated: "Yes", year: "12", month: "3"})
CREATE (product8: Product {product_group: "69", ingredient: "AMANTADINE HYDROCHLORIDE", strength: "100MG", mdr_unit_type: "TAB", arated: "Yes", year: "12", month: "3"})
CREATE (product9: Product {product_group: "81", ingredient: "AMIODARONE HYDROCHLORIDE", strength: "200MG", mdr_unit_type: "TAB", arated: "Yes", year: "12", month: "3"})
CREATE (product10: Product {product_group: "82", ingredient: " AMITRIPTYLINE HYDROCHLORIDE", strength: "10MG", mdr_unit_type: "TAB", arated: "Yes", year: "12", month: "3"})
CREATE (product11: Product {product_group: "102", ingredient: "AMOXICILLIN", strength: "300MG;15MG", mdr_unit_type: "TAB", arated: "Yes", year: "12", month: "3"})
CREATE (product12: Product {product_group: "123", ingredient: "ASPIRIN; BUTALBITAL; CAFFEINE; CODEINE PHOSPHATE", strength: "325MG;50MG;40MG;30MG", mdr_unit_type: "TAB", arated: "Yes", year: "12", month: "3"})
CREATE (product13: Product {product_group: "133", ingredient: " ATENOLOL", strength: "300MG;15MG", mdr_unit_type: "TAB", arated: "Yes", year: "12", month: "3"})
CREATE (product14: Product {product_group: "136", ingredient: "ATENOLOL; CHLORTHALIDONE", strength: "100MG;25MG", mdr_unit_type: "TAB", arated: "Yes", year: "12", month: "3"})
CREATE (product15: Product {product_group: "139", ingredient: "ATROPINE SULFATE; DIPHENOXYLATE HYDROCHLORIDE", strength: "300MG;15MG", mdr_unit_type: "TAB", arated: "Yes", year: "12", month: "3"})
CREATE (product16: Product {product_group: "141", ingredient: "AZATHIOPRINE", strength: "50MG", mdr_unit_type: "TAB", arated: "Yes", year: "12", month: "3"})
CREATE (product17: Product {product_group: "148", ingredient: "BACLOFEN", strength: "10MG", mdr_unit_type: "TAB", arated: "Yes", year: "12", month: "3"})
CREATE (product18: Product {product_group: "153", ingredient: " BENZONATATE", strength: "100MG", mdr_unit_type: "TAB", arated: "Yes", year: "12", month: "3"})
CREATE (product19: Product {product_group: "154", ingredient: "BENZTROPINE MESYLATE", strength: "0.5MG", mdr_unit_type: "TAB", arated: "Yes", year: "12", month: "3"})
CREATE (product20: Product {product_group: "181", ingredient: "BUMETANIDE", strength: "0.5MG", mdr_unit_type: "TAB", arated: "Yes", year: "12", month: "3"})
```

### 2/ Establishing relationships between nodes


### 3/ Delivering insights
