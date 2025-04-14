# sit737-2025-prac6c

Part I

Step 1: Checked the application status by using 'kubectl get pods' & 'kubectl get services'
Step 2: Use 'kubectl port-forward service/myservice 3000:3000' to run it on localhost:3000
Step 3: Open localhost:3000 and test each endpoints

Part II

Step 1: I updated the node.js application 'calculator.js' by adding two new operation endpoints 'increment' & 'decrement'
Step 2: After adding the two endpoints, created a new image into docker named 'justinls1/calculator1:latest' for the new application
Step 3: After that, i modified all relevant files that contians image fields and repalce them with the new docker image tag
Step 4: Ran the service through powershell and the two new operations are working as expected