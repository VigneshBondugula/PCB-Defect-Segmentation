# PCB Defect Segmentation


## Documentation:

[https://www.notion.so/PCB-Defect-Segmentation-3dc0c3dd1f6f4422979d6b90ed79713b?pvs=4](https://www.notion.so/PCB-Defect-Segmentation-3dc0c3dd1f6f4422979d6b90ed79713b?pvs=21)

## Flow Chart :

![diagram-20231219 (3).png](figures/diagram-20231219_(3).png)

## Example:

![diagram-20231219 (2).png](figures/diagram-20231219_(2).png)

## How to run:

- First, download the dataset from,
[Defects Instance Segmentation Dataset](https://universe.roboflow.com/diplom-qz7q6/defects-2q87r/dataset/8)

- Copy the downloaded folders into data folder and run the notebooks given in it to extract the masks. If only masks for short circuit defects need to be generated run dataset_shot_circ.ipynb. Generated train_final, val_final and test_final folders need to be renamed to train, val and test.
- Run the PCB-segmentation.ipynb, make sure you have all the necessary python libraries.
