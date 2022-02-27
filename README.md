# MRI-Data-Analysis
Documenting my Internship pre-processing and analysis of Neuro-imaging data for patients with
alcohol use disorder (AUD)

My work within the internship comprised the following sections:

1. Writing a pipeline to import T1w images of subjects, convert them to
    BIDS format, generate `participants.csv`, and upload them to our servers.
2. Extending the pipeline to download subjects behavioural data and survey results.
3. Pre-processing T1w images using FreeSurfer to generate brain features (stats)
4. Apply Dimensionality Reduction techniques on both extracted brain features and subjects
    meta-data to visualize the data.
5. Studying and deciding what clustering algorithms to be used to help achieve a non-trivial clustering
    of the subjects data to possible subtypes of Aclohol Use Disorder
