## Training and hyperparameter tuning of the Attention U-Net model.

#### The notebook will save three outputs for which the user has to generate the following folder structure:

    data/
    
        model/
    
              att_unet/
          
                      weights/
                              "the notebook will save .hdf5 file with the best weights 
                               of each parameters combinations"

                      plots/
                            "the notebook will save training and validation learning and loss curves"

                      results/
                             "the notebook will save a .csv file containing all details of each 
                              models with respectives evaluation scores on the test data"           

Credits for the Attention U-Net architecture: [Abraham et al., (2019)](https://ieeexplore.ieee.org/abstract/document/8759329).
