# dataset_pingpong
Dataset containing the accelerometer and gyroscope data regarding 6 different strokes of Ping Pong:

- Forehand Push
- Forehand Drive
- Forehand Topspin
- Backhand Push
- Backhand Drive
- Backhand Topspin

This dataset is in JSON format and was created with the movements of 10 different persons, using an iPhone 6S and DeviceMotion events for recording the data. It contains the following fields:

- "user" : user id
- "stroke" : type of stroke
- "ax" : accelerometer data in X
- "ay" : accelerometer data in Y
- "az" : accelerometer data in Z
- "rx" : rotation data in X
- "ry" : rotation data in Y
- "rz" : rotation data in Z
