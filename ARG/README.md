##### ARG

ARG is used to supply few variables at the image creation.

1. ARG is the only instruction you can use before FROM. ARG declared before cant be accessed after FROM

##### Using ENV and ARG for the best results.

1. Create one env variable and assign the value of ARG to that
2. Then we can access ARG values through ENV both in image and container