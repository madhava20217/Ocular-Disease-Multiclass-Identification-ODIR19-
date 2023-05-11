# README

Contributors:

1. Bhagesh Gaur (2020558)
2. Madhava Krishna (2020217)
3. Sanyam Goyal (2020116)

The project involves multilabel classification using the ODIR dataset.

The detailed report can be found here: <a href = "DL_End_Report.pdf">DL Report Final</a>.

The broad steps involved are:

1. Preprocessing the data to extract single eye-features (credits to Jordi Corbella).
2. Creating histogram equalised images of the eye-images.
3. Train Swin-T transformer with early-fusion of image and other features (age, sex).
4. Using an ensemble of Swin-T vision transformers.
