
# Zoe Depth Estimation 

Zoe Depth Estimation is a model that predicts depth from a single image, turning 2D photos into 3D depth maps.


## Usage/Examples

### CLI Usage
```bash
usage: cli.py [-h] input_image output_image

Depth estimation

positional arguments:
  input_image   Path to input image.
  output_image  Path to output depth map.

options:
  -h, --help    show this help message and exit
```

### API Usage
```
http://127.0.0.1:8000/predict
```

  
## Installation

Install depth estimation project with pip

```bash 
  pip install -r requirements.txt
```
    
## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`IMG_API_KEY`

  
## Deployment

To deploy this project run

```bash
  docker build -t depth_estimation.
  docker run -d -p 8041:8041 depth_estimation
```

  
## License

[MIT](https://choosealicense.com/licenses/mit/)

  