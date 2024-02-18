What is SplitFolder?
split-folders is a Python library that simplifies the process of splitting and organizing datasets into train, validation, and test sets. It's a lifesaver for machine learning practitioners dealing with large datasets.


# pip install split-folders

import splitfolders

# Define the input folder and output folders
input_folder = "path/to/dataset"
output_folder = "path/to/output"

# Specify the split ratios (e.g., 80% train, 10% validation, 10% test)
split_ratios = (0.8, 0.1, 0.1)

# Use splitfolder to perform the split
splitfolders.ratio(input_folder, output=output_folder, seed=42, ratio=split_ratios, group_prefix=None)

To learn more, visit the official https://lnkd.in/dTQ6HVRy
