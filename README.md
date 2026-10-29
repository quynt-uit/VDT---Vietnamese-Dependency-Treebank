# VDT: A Vietnamese Dependency Treebank via Semi-Automatic Annotation

This repository contains the implementation and resources for **VDT (Vietnamese Dependency Treebank)**. VDT is a high-precision linguistic resource developed using a semi-automatic annotation framework designed to bridge the gap between scalability and quality.

## Key Highlights

- **Custom Label Set:** Introduces **83 dependency relations** designed to cover specific characteristics of Vietnamese, including Sino-Vietnamese elements and classifier nouns.
- **High Precision:** Combines algorithmic conversion with manual post-editing to improve annotation quality.
- **Scalability:** Provides a rule-based approach for converting constituency trees from **NIIVTB-1** into dependency structures.

## Construction Pipeline

The construction of VDT follows a two-stage pipeline:

1. **Phase 1: Automatic Conversion**  
   A specialized rule-based converter transforms the **NIIVTB-1** constituency treebank into an initial dependency version, referred to as VDT Auto.
2. **Phase 2: Manual Post-editing**  
   Well-trained annotators perform rigorous manual editing on *VDT Auto* to produce the final gold-standard treebank, VDT.

## Data Access and Copyright Policy

Due to copyright restrictions, we provide only annotations. To obtain the complete VDT treebank with original raw texts, users can follow either of the two options below:

**Option 1: Reconstruct the treebank**

1. Obtain the VLSP raw text files from the authorized source ([VLSP](https://vlsp.hpda.vn/)).
2. Run the merge script to combine the raw texts with the VDT annotations. (The script will be uploaded soon.)

**Option 2: Contact the corresponding author**

For inquiries about data access, please contact the corresponding author at quynt@uit.edu.vn

**License:** The original VDT annotations and repository materials released by the VDT authors are licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License (CC BY-NC-SA 4.0)](https://creativecommons.org/licenses/by-nc-sa/4.0/).

## References

- [NIIVTB: Vietnamese Constituent Treebank](https://github.com/mynlp/niivtb)
- Nguyen, Q. T., Miyao, Y., Le, H. T. T., & Nguyen, N. T. H. (2018). [Ensuring Annotation Consistency and Accuracy for Vietnamese Treebank](https://link.springer.com/article/10.1007/s10579-017-9398-3). *Language Resources and Evaluation, 52*(1), 269–315.

