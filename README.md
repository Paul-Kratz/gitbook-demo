# HyperCurrent

## 

### HyperCurrent React app

#### Running app locally

**In order to run the app locally**

**yarn dev or npm run dev**

#### Building Docker image

**In order to build the image, run the following command**

`docker build -t <IMAGE_NAME_HERE> .`

In order to run the image use the following command  
`docker run -e API_URL="<YOUR_URL>" -e AUTH_ISSUER="<AUTH_ISSUER>" -e AUTH_CLIENT_ID="<AUTH_CLIENT_ID>" -p 8080:80 -d <IMAGE_NAME_HERE>`



