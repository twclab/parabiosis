<p align="center">
  <img src="./parabiosis.png" alt="alpenglow"/>
</p>

# Parabiosis
The repository contains jupyter notebooks descripbing downstream analyses of the `Molecular hallmarks of heterochronic parabiosis at single cell resolution`.
Notebooks describe quality control, batch correction, cell type annotation and differential gene expression steps starting from the raw, unfiltered, aligned count matrices. The list of notebooks:
1. Quality control, PC calculation, batch correction, and clustering
2. Batch correction metrics calculation (2.1) includes LISI score claculation in R
3. KNN based cell type annotation
4. Differential Gene Expression
5. Final data formatting steps
6. Data conversion to RDS

## Data

- Raw data is available on [AWS](https://s3.console.aws.amazon.com/s3/buckets/czb-tabula-muris-senis?region=us-west-2&tab=objects)
- Annotated read count data matrices are available on [Figshare](https://figshare.com/projects/Molecular_hallmarks_of_heterochronic_parabiosis_at_single_cell_resolution/127628)  in `h5ad` and in `RDS` formats

## Online Data Browser

Explore the dataset via our [interactive data browser](https://ccb-web.cs.uni-saarland.de/parabiosis/)
