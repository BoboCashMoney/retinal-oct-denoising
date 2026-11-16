# Retinal OCT Denoising

This short image-processing study for the Bowden Biomedical Optics Laboratory
compares Gaussian, median, and bilateral filters on retinal OCT images. I’ll
compare how much each filter reduces noise, how well it preserves visible
retinal layers, and how long it takes to run.

## Dataset

I’ll use Daniel Kermany’s [Labeled Optical Coherence Tomography (OCT) for
Classification dataset](https://data.mendeley.com/datasets/rscbjbr9sj/1).
The initial comparison will use scans from the `NORMAL` category of the
test split.
