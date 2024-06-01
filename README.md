
### Machine learning for a better and safer life. 


# self-supervised-model-for-construction-machines

## Motivation: 

The contributions of this work are:
* Design a first-of-its-own generalizing skeleton-generating model for complex kinematic systems using synthetic and real datasets and leveraging deep neural networks and machine learning for pose estimation purposes.
* Automatically generate a synthetic dataset with annotation using simulators for pose estimation tasks. This data represents mainly one object class of excavator.
* Design and implement a state-of-the-art self-supervised deep neural network model based on the SimCLR model to generate a skeleton for a heavy construction machine ‘excavator’ using a smaller amount of annotated dataset.
* Minimize the domain shift between the simulated and real situations using a small dataset from a real environment, which improves the model’s performance on real-world data.

## Dataset and keypoints definition:
The definition of keypoints within literature and this work: 
![Keypoint_def](https://github.com/alaa-shubbak/self-supervised-model-for-construction-machines/blob/main/images/keypoint_definitions.png)

dataset from the simulations: 

<img src="https://github.com/alaa-shubbak/self-supervised-model-for-construction-machines/blob/main/images/issac%20all_results.png" width="350"> <img src="https://github.com/alaa-shubbak/self-supervised-model-for-construction-machines/blob/main/images/matlab_results.png" width="350">

samples from real ACID dataset[1]


## Proposed Deep neural network model:
The proposed model and deep neural network architecture: 

![general2](https://github.com/alaa-shubbak/self-supervised-model-for-construction-machines/blob/main/images/smart.jpg)


## Results: 

Evaluation : 

![results](https://github.com/alaa-shubbak/self-supervised-model-for-construction-machines/blob/main/images/table_results_self_supervised.png)

Samples of Results: 

![results1](https://github.com/alaa-shubbak/self-supervised-model-for-construction-machines/blob/main/images/results/samples_results_self_super_pose.png)

## Citation: 

    @inproceedings{alshubbak2023self,
    title={A Self-supervised Pose Estimation Approach for Construction Machines},
    author={Alshubbak, Ala’a and G{\"o}rges, Daniel},
    booktitle={International Symposium on Visual Computing},
    pages={397--408},
    year={2023},
    organization={Springer}
    }

