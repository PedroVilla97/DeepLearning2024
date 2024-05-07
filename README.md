Repository for the Deep Learning course at Jheronimus Academy of Data Science (JADS)
List of contributors:

    Krzysztof Wiesniakowski
    Chigozie Ifepe
    Pedro Villadangos Benavides

The goal of the project was to perform evaluate deep learning model on novel SEN12-FLOOD dataset presented by Rambour et al. (2020). 

Quick explanation of the project structure:
 - `project_report` contains all files which are necessary to generate report in Latex environment. There is also a PDF file which is the main report file and presents our main findings
 - `deep_learning_flooding.ipynb` Jupyter notebook where preprocessing the data, training and evaluating the deep learning model has been defined
 - `environment.yaml` file which specifies all necessary dependencies, libraries, and their respective versions for replication purposes.
 - `sample_data` is the sample data presented on International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Volume XLIII-B2-2020, 2020 XXIV ISPRS Congress (2020 edition) and can be accessed through this link [https://clmrmb.github.io/SEN12-FLOOD/]

Contained within this GitHub repository are sample folders showcasing the data utilized for training, validation, and testing of our deep neural network for flood detection. The repository includes JSON files that contain metadata for both Multispectral and SAR satellite data. Additionally, the primary Python notebook used to achieve the results is also provided.

In the function 'select_balanced_subset' it is possible to select the percentage of folders from the available folders to analyze and run in the deep neural network

