# Simple Node App with Docker

## Specifications

  Docker: 26.1.1
  
  macOS: Sonoma 14.5


## Instructions
  1. Command to create a simple-node Docker image:
     
          docker built -t simple-node .

  2. Command to run image:

           docker run --rm -p 3000:3000 simple-node

  3. If you want to remove the image run:

           docker rm simple-node
