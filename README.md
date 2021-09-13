# mrc-fabric-network
How to Run the Environment
1. Run Fabric Network and deploy chaincode on it. ##

When you run the above environment, you might see your previous environment running with all docker containers still up and chaincode deployed. If that is the case you can skip this step. If its a new environment, run the following command.

    cd /usercode/infra-basic-network && ./exercise-1.sh && cd /usercode/chaincode && ./exercise-2.sh

2. Start the API server ##
```
cd /usercode/infra-basic-network && ./exercise-1.sh && cd /usercode/chaincode && ./exercise-2.sh
```    
3. Test your application 

Click your application url now! Click the url shown above the terminal tab - below the code.
- Visit the /enrollAdmin endpoint first so admin user’s credentials are generated
- Visit the /query endpoint to view all data that was put in ledger by our chaincode init method
- Visit the /invoke endpoint to enter new data into ledger
- Visit the /query endpoint to verify that new data has been added to ledger
