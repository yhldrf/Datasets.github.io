<!-- # SHREC 2020 Track: 3D Point Cloud Semantic Segmentation for Street Scenes -->

## Motivation & Task

Scene understanding of large-scale 3D models of an outer space is still a challenging task. With the development of computer vision techniques, it’s cost-effective to develop a solution for large-scale 3D scenes related tasks, e.g. semantic segmentation for 3D street scenes. 

In this track, we provide large scale 3D point clouds for street scenes. Our goal is to localize and segment semantic objects from large-scale street scene 3D point clouds. We also provide manually labelled ground-truth for training and validation. We expect to encourage researchers to try out different methods, including both deep learning and traditional machine learning techniques.

## Dataset

The dataset includes over 100 manually annotated street-scene 3D point clouds. The point clouds are recorded by a lidar sensor on a car. Each point cloud represents a street scene and contains a group of objects. We use the open source software [CloudCompare](http://cloudcompare.org/) to manually label point clouds. Objects are labelled into 5 meaningful classes and an extra `undefined` class. They are:

(1) `Building` (2) `Car` (3) `Ground` (4) `Pole` (5) `Vegetation` (6) `Undefined`

To fit for a learning system, the dataset is split into training and test sets with the ratio 80% and 20%. For both training and test sets, we provide ground-truth semantic labels.

[Download dataset]() (Avaliable soon!)

## Registration

To participate in the track, please send us an email. In it, please confirm your interest in participation and if applicable, please also mention your affiliation and co-authors.

## Submission

From participants, no later than the deadline mentioned in the schedule, we expect results submitted along with a one-page description of the method used to generate them. Results should be presented as a collection of estimated point clouds containing their semantic labels.

## Evaluation

The main goal of the track is to segment semantic objects out of the street-scene 3D point clouds. For different classes, IoU (Intersection over Union) is one of the main evaluation metrics. For the whole dataset, the unweighted average of IoU (mIoU) of each class and global accuracy are import indicators. We set these three metrics as the main evaluation indicators.

## Organizers

- Tao Ku, Utrecht University, Department of Information and Computing Sciences
- Remco C. Veltkamp, Utrecht University, Department of Information and Computing Sciences
- Bas Boom, Cyclomedia Technology

To contact the organizers, please contact [t.ku@uu.nl](mailto:t.ku@uu.nl)

## Schedule

The registration and submission deadlines are in AoE (Anywhere on Earth) timezone.

    - March 2, 2020: The dataset is available.
    - March 10, 2020: Registration deadline.
    - March 24, 2020: Submission deadline of the results.
    - April 3, 2020: Track submission to SHREC for review.
    - May 1, 2020: Reviews done, first stage decision on acceptance or rejection
    - May 22, 2020: First revision.
    - May 29, 2020: Second stage decision on acceptance or rejection.
    - June 12, 2020: First revision.
    - June 19, 2020: Final decision on acceptance or rejection.
    - September 1, 2020: Publication online in Computers & Graphics.
    - September 4-5, 2020: Eurographics Workshop on 3D Object Retrieval 2020, featuring SHREC 2020.

## References

1.	Zolanvari, S. M., Ruano, S., Rana, A., Cummins, A., Silva, R. E., Rahbar, M., & Smolic, A. (2019). DublinCity: Annotated LiDAR Point Cloud and its Applications. arXiv: Computer Vision and Pattern Recognition.
