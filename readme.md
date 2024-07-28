##tanX_app

## Running the tanX:
![image](https://github.com/user-attachments/assets/b3dd304a-fd24-456e-98f9-694696369189)

## Summarize the Test cases:
![image](https://github.com/user-attachments/assets/29384546-7d46-48ac-9f71-e23892c7f08a)

## Pushing on Github:
![image](https://github.com/user-attachments/assets/160ce61c-596e-4236-95ff-3a33e4747b46)

## Dockerization

The application is dockerized into two separate services: one for the main task and one for testing.

### Building the Docker Images

1. Build the main application image:
       
   docker build -t orders-analysis .
    

2. Build the test image:
       
   docker build -f Dockerfile.test -t orders-analysis-test .
    

### Running the Docker Containers

1. Run the main application container:
    
   docker run --rm orders-analysis
    

2. Run the test container:
       
   docker run --rm orders-analysis-test
    
