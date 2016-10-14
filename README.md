# WSO2 API Manager 2.0.0

Docker image to install WSO2 API manager 2.0.0. Based on https://github.com/ihcsim/docker-wso2apim

## Usage

1. To pull: docker pull osblue13/wso2am-2.0.0
2. To run: docker run --rm --name your_container_name -p 9443:9443 -p 9736:9736 -p 8243:8243 -p 8280:8280 -p 10397:10397 -p 7711:7711 osblue13/wso2am-2.0.0


## Self-hosted

If you have wso2 zip downloaded, it will easier to to run the selfhosted image

1. Download the wso2 zip from http://wso2.com/products/api-manager/
2. Put the zip file in self-hosted folder
3. Run Docker


