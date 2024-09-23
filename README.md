# InstructPen: Generative digital ink for LLMs

* work in progress

We pretrain InstructPen with text-to-mouseevent and image-to-mouseevent task via document level transcription on [pen-simulator](https://github.com/xuguodong1999/pen-simulator).

In post training stage, we deploy the following tasks:

1. arithmetic draft like columnar addition and [multiplication](https://github.com/xuguodong1999/pen-simulator)
2. bounding box generation in object detection
3. mask generation in instance segmentation
4. ...
