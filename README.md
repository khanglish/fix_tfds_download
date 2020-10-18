# Fix Tensorflow Datasets Quota Exceed on Drive

This repos store modified files from tensorflow datasets to repair the Bug: GDrive Quota Exceed

How I handle this bug:

1> Manually download the original datasets from tensorflow datasets link.

2> Upload it to my google drive.

3> Modified the links in 2 files: 

~/.../tensorflow_datasets/image/[dataset_name]

~/.../tensorflow_datasets/url_checksums/[dataset name]
