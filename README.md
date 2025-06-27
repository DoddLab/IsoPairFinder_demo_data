# IsoPairFinder Demo Data

This repository contains demo data for the IsoPairFinder project, which is used for isotopic labeling experiments and mass spectrometry data analysis. The data provided here can be used to test and demonstrate the IsoPairFinder workflow. This demo data set belongs to the [uric acid catabolism study](https://www.biorxiv.org/content/10.1101/2025.04.24.650524v1). We acquired the stable isotope tracing metabolomics for hyuA mutant and WT samples which are curated with 12C uric acid and 13C uric acid. The raw data are processed by the MS-DIAL to generate peak tables. This demo data includes processed peak tables and raw mass spectrometry files.

## Directory Structure

- `peak_table_C12.csv` / `peak_table_C13.csv`: Peak tables for 12C and 13C labeled samples.
- `sample_info.csv`: Metadata about the samples included in the dataset.
- `hyuA_12C/`, `hyuA_13C/`, `WT_12C/`, `WT_13C/`: Folders containing `.mzML` files for different sample groups and isotopic labels.
- `ms2/`: Contains MS2 data files for pooled QC samples.

## Usage

These files are intended for use with the IsoPairFinder tool or similar mass spectrometry data analysis pipelines. You can use them to:

- Test the IsoPairFinder workflow
- Validate data processing scripts
- Demonstrate data analysis pipelines

## File Descriptions

- **peak_table_C12.csv / peak_table_C13.csv**: Processed peak tables for 12C and 13C samples.
- **sample_info.csv**: Sample metadata including group, label, and file associations.
- **[group_label]/**: Folders containing raw `.mzML` files for each sample group and isotopic label.
- **ms2/**: MS2 spectra for pooled QC samples.

## Citation

If you use this data in your research or publication, please cite the IsoPairFinder project accordingly.

- Liu, Y. et al. Gut bacteria degrade purines via the 2,8-dioxopurine pathway. Nature Microbiology Accepted, (2025).
- Zhou, Z. et al. IsoPairFinder: An R package for identifying potential intermediates from Stable Isotope Tracing metabolomics data, In preparation, 2025

## Contact

For questions or feedback, please contact:

**Zhiwei Zhou**  
Department of Pathology, Stanford University  
Email: zhouzw@stanford.edu

---

## License
<a rel="license" href="https://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a> 
This work is licensed under the Attribution-NonCommercial-NoDerivatives 4.0 International (CC BY-NC-ND 4.0)