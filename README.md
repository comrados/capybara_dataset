# Capybara Dataset

![](https://raw.githubusercontent.com/freds0/capybara_dataset/main/images/train/1.jpeg)

*"The capybara or greater capybara (Hydrochoerus hydrochaeris) is a giant cavy rodent native to South America. It is the largest living rodent and a member of the genus Hydrochoerus. The only other extant member is the lesser capybara (Hydrochoerus isthmius). Its close relatives include guinea pigs and rock cavies, and it is more distantly related to the agouti, the chinchilla, and the coypu. The capybara inhabits savannas and dense forests and lives near bodies of water. It is a highly social species and can be found in groups as large as 100 individuals, but usually lives in groups of 10–20 individuals. The capybara is not a threatened species and it is hunted for its meat and hide and also for grease from its thick fatty skin."*

Source: https://en.wikipedia.org/wiki/Capybara

This is a dataset was collected to train my own Capybara detector with TensorFlow's Object Detection API. Images are from Google. The dataset contains 200 images of capybaras (180 are used for training and 20 for validation) which were manually box-bound labelled using the tool [LabelImg](https://github.com/tzutalin/labelImg) to prepare the dataset in the Pascal VOC XML format. This project is a tropical version of the [Raccoon Dataset](https://github.com/datitran/raccoon_dataset), which I was inspired by.

# Capybara Segmentations

[MSCOCO-like segmentations of 165 samples from the Capybara Dataset](https://github.com/comrados/capybara_dataset/blob/main/data/capybara_coco_segmentations_165_samples.json). 


# Copyright

See [LICENSE](https://github.com/freds0/capybara_dataset/blob/main/LICENSE) for details. Copyright (c) 2021 Fred Oliveira.
