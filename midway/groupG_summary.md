# Summary
Project in Data Science
Group: G (Greedy Geckos)

* Aniela Marta Ciecierska
* Francisco Gonçalves Medeiros Lemos Moreno
* Jakub Piotr Gąsior
* Jonas Drøivoldsmo Lesund
* Michaela Macejovska




As a task for Projects in Data Science, the group analyzed the relevant pictures in order to take conclusions about possible occurrence of cancer. 
By researching several webpages (Seladi-Schulman, 2022) (Allan C. Halpern, 2021) (Osborn, s.d.) (Anadolu-Brasie R, 2008) (Michael J. Greco, 2023), 
the team gathered some information about different types of cancer and categorized the pictures into each disease. 
Since the images are being observed on either a phone or laptop screen and the research is conducted by unexperienced students, some images were categorized into more than one group. 
The findings are as follows:


*	Actinic keratosis: A discolored, rough spot, up to 1 cm in diameter, often with hyperkeratotic layers, sometimes taking the form of a cutaneous horn. (54 images fall under this category).

*	Basal cell carcinoma: Most often a pale color nodule, well demarcated from the surrounding skin, with translucent vessels. In more advanced forms with the presence of an ulcer with a ridged edge. 
  (39 images fall under this category).

*	Melanoma: Asymmetrical lesion, with irregular borders, non-uniform color (from light brown to black) and diameter over 6 mm. (2 images fall under this category).

* Nevus: Symmetrical lesion, with even borders, uniform color (from light brown to black) and diameter up to 6 mm. (9 images fall under this category).

* Squamous cell carcinoma: From an erythematous, scaly papule to an ulcerated, disintegrating Tumor. (18 images fall under this category).

*	Seborrheic keratosis: More or less raised lesions above the skin surface, sometimes pedunculated, with a smooth, lumpy, or rough surface, pale or brown color. (16 images fall under this category).



## Missing data	

Each skin lesion is made up of a maximum of 26 features, where each line denotes a skin lesion, and each column denotes a feature. It seems that there is a pattern of missing values. 
The same values are missing in every observation. There are some cells that contain "UNK" indicating unknown or missing data (“background_father”, “background_mother”, “grew”, “changed”, “itch”). 
Some rows have missing values, where the data is missing or was not recorded (“smoke”, “gender”, “cancer_history”, “has_piped_water”, etc.).

The reasons for missing data could range from data entry errors, non-response from the patients or medical professionals to systematic issues with how the data is recorded or transferred. 

Handling missing data depends on the context and the importance of the missing information. For the column, which seems to be a unique identifier for diagnosis, 
missing data might be more critical and could potentially indicate cases where the diagnosis was not recorded. Before handling the missing data, it's important to understand why it is missing.
For instance, if the missing data is not random (i.e., there is a pattern to the absence), simply deleting or imputing without investigating could introduce bias into any conclusions drawn from the data.

## Quality of the images from the data set.

It is rather challenging to determine which images qualify as low quality as some have a considerably higher resolution than others, meanwhile those that have “lower quality” are still 
not necessarily considered bad quality, as the cancer is quite visible even on the images with lower resolution. As a result, these images cannot, in this case, be considered of too low resolution 
to be able to draw any conclusions about the type of cancer shown. 


## Low quality photos:
PAT_246_377_159.png
PAT_153_233_45.png
PAT_356_4511_960.png
PAT_1618_2771_628.png

* photos deleted form the data set. 

## Citation of the dataset that was downloaded:

Pacheco, Andre G. C.; Lima, Gustavo R.; Salomão, Amanda S.; Krohling, Breno; Biral, Igor P.; de Angelo, Gabriel G. ; Alves Jr, Fábio  C. R. ; Esgario, José G. M.; Simora, Alana C. ; 
Castro, Pedro B. C. ; Rodrigues, Felipe B.; Frasson, Patricia H. L. ; Krohling, Renato A.; Knidel, Helder ; Santos, Maria C. S. ; Espírito Santo, Rachel B.; Macedo, Telma L. S. G.; 
Canuto, Tania R. P. ; de Barros, Luíz F. S. (2020), “PAD-UFES-20: a skin lesion dataset composed of patient data and clinical images collected from smartphones”, Mendeley Data, V1, doi: 10.17632/zr7vgbcyr2.1
https://data.mendeley.com/datasets/zr7vgbcyr2/1
