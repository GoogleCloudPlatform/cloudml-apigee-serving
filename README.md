# Serving Machine Learning Models using Apigee Edge & Cloud ML Engine

This repository contains the accompanying code for the tutorial at
[https://cloud.google.com/solutions/serving-models-apigee-edge-ml-engine](https://cloud.google.com/solutions/serving-machine-learning-models-using-apigee-edge-and-ml-engine).

### Directories
* `apiproxy` - Apigee [API
  proxy](https://docs.apigee.com/api-platform/fundamentals/understanding-apis-and-api-proxies)
  to serve an app-facing API, which forwards prediction requests to a backend API hosted on [Cloud Machine Learning Engine](https://cloud.google.com/ml-engine) (using [Online Prediction](https://cloud.google.com/ml-engine/docs/tensorflow/online-predict)).
* `model` - Sample pre-trained TensorFlow model for [predicting income using census data](https://github.com/GoogleCloudPlatform/cloudml-samples/tree/master/census).

### Installation
See the [tutorial page](https://cloud.google.com/solutions/serving-machine-learning-models-using-apigee-edge-and-ml-engine) for full instructions.
