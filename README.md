# Landmark Recognition (Google ML challenge)

Landmark recognition challenge in which unbalanced dataset of 105 GB is provided and have to train model on that dataset for prediction

## Description

The live link to use the web application is:
https://projds-env.eba-pytuib3z.us-east-2.elasticbeanstalk.com/

Upload an image and prediction will be shown there.

## Details

This repo contains the flask application code as well as the python notebook which trains the model. In this we are using resnet model as it is light and less computations are required. This model uses batch training to train model as dataset is extremely large so we can't accommodate all photos in RAM. 

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
