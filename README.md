# CarND-Semantic-Segmentation
Project developed for the Self-Driving Car Engineer Nanodegree Program, for a (way) more (and undocumented) complete implementation using the Mapillary database, see [here](https://github.com/stesalati/RoadPerceptionSemanticSegmentation).

### Model Documentation

#### Architecture
An architecture based a pre-trained VGG-16 network, modified as proposed [here](https://people.eecs.berkeley.edu/~jonlong/long_shelhamer_fcn.pdf), was used.

#### Training
The following hyperparameters were used:
- keep_prob: 0.5
- learning_rate: 0.001
- epochs: 50
- batch_size: 10

The loss per batch is steadily decreasing. For clarity, the following plot describes only the last 49 epochs:

![](readme_images/loss.png)

#### Sample results
![](readme_images/01.png)

![](readme_images/02.png)

![](readme_images/03.png)

![](readme_images/04.png)

![](readme_images/05.png)

![](readme_images/06.png)

![](readme_images/07.png)

![](readme_images/08.png)
