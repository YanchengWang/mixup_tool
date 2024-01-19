# mixup_tool
Examples can be found in [mixup_example.ipynb](mixup_example.ipynb)
### Usage
`from customized_mixup import customized_mixup`

`images, labels = customized_mixup(images, labels, num_classes, alpha=1.0, mixup_data_only=True, enlarge_scale=2)`

`alpha`: alpha for the Beta distribution used for sampling interpolation factors. We set the default value of alpha to 1.

`enlarge_scale`: The enlarged scale of the dataset with mixup. We generate augmented `enlarge_scale` images for each image in the training set

`mixup_data_only`: Whether we only use mixup augmented data.

`num_classes`: Number of classes
