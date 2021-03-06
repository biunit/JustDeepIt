=======
PPD2013
=======

Dataset
=======

.. <dataset>

.. code-block:: sh
    
    # download tutorials/PPD2013 or clone JustDeepIt repository from https://github.com/jsun/JustDeepIt
    git clone https://github.com/jsun/JustDeepIt
    cd JustDeepIt/tutorials/PPD2013

    # download dataset (Plant_Phenotyping_Datasets.zip) from http://www.plant-phenotyping.org/datasets
    # and put Plant_Phenotyping_Datasets.zip in JustDeepIt/tutorials/PPD2013
    
    # decompress data
    unzip Plant_Phenotyping_Datasets.zip
    
    # create folders to store images for training and inference
    mkdir -p inputs/train_images
    mkdir -p inputs/query_images

    # select 4 images and the corresponding mask images for training
    cp Plant_Phenotyping_Datasets/Tray/Ara2013-Canon/ara2013_tray01_*.png inputs/train_images/
    cp Plant_Phenotyping_Datasets/Tray/Ara2013-Canon/ara2013_tray09_*.png inputs/train_images/
    cp Plant_Phenotyping_Datasets/Tray/Ara2013-Canon/ara2013_tray18_*.png inputs/train_images/
    cp Plant_Phenotyping_Datasets/Tray/Ara2013-Canon/ara2013_tray27_*.png inputs/train_images/

    # use all images for inference
    cp Plant_Phenotyping_Datasets/Tray/Ara2013-Canon/*_rgb.png inputs/query_images



.. </dataset>



