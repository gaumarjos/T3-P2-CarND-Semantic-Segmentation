# CarND-Semantic-Segmentation
Project developed for the Self-Driving Car Engineer Nanodegree Program, for a (way) more complete implementation using the Mapillary database, see [here](https://github.com/stesalati/RoadPerceptionSemanticSegmentation).

### Model Documentation

#### Architecture
An architecture based a pre-trained VGG-16 network, modified as proposed [here](https://people.eecs.berkeley.edu/~jonlong/long_shelhamer_fcn.pdf), was used.

#### Training
The following hyperparameters were used:
- keep_prob: 0.5
- learning_rate: 0.001
- epochs: 50
- batch_size: 10

The loss per batch is steadily decreasing. A plot is shown as follows:

#### Sample results
![](./runs/1517315452.771893/um_000000.png =250x)

![](./runs/1517315452.771893/um_000000.png =250x)

![](./runs/1517315452.771893/um_000000.png =250x)

![](./runs/1517315452.771893/um_000000.png =250x)

![](./runs/1517315452.771893/um_000000.png =250x)

![](./runs/1517315452.771893/um_000000.png =250x)
