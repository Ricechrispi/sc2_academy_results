# SC2 Academy Results

This repository contains all the results from using the [SC2 Academy](https://github.com/Ricechrispi/sc2_academy) framework.

Additionally, the _SC2_Academy.ipynb_ notebook illustrates how to use the _SC2 Academy_ framework for yourself.


## Results

In the *data* folder, you will find extracted .csv files for each mini-game that depict the progress during training and (final) evaluations.

## Using the existing agents
In the *results* folder, you will find checkpoints for each mini-game that can be used to continue training.
The easiest way to do this is as follows:
* open the _SC2_Academy.ipynb_ notebook in COLAB
* follow the instructions there to setup the SC2 Academy
* download the folder with the name of the mini-game you wish to continue training in, e.g. MoveToBeacon
* upload this folder to the COLAB instance

The target location of the folder should again be in the 'results' folder.
If it does not exist already, create it.
The final folder structure should be as follows:
```
content/
    results/
        MoveToBeacon
        ...
``` 
The _content_ folder is usually hidden in COLAB and represents the top-level folder.

You can now continue training or evaluate the agent. 
Be sure to set the hyper-parameters to the same values found in the _run_description.txt_ file.

If you have any questions, please contact me or open an issue.