# VPC-Peering-connection
communication between two instances from different Account regions
### Create 1 instance in a different account (make sure to give ICMPIPv4) and try ping with public IP it will communicate then try with private ip it will not so to communicate with private IPs we need a secure peering between the two VPCs

![Screenshot 2024-03-27 082919](https://github.com/Tanay03Trivedi/VPC-Peering-connection/assets/160705084/458c6753-a479-4c4e-a0de-fe4649d0a482)

![Screenshot 2024-03-27 083012](https://github.com/Tanay03Trivedi/VPC-Peering-connection/assets/160705084/043d2ef9-f857-4e07-b281-01b5e07fd9ca)

## In vpc go to vpc peering connection in any account type the name .vpc in the primary account you want to select then give the account ID in which the second vpc we create and vpc ID then establish the connection make sure the subnet does not overlap each other

![Screenshot 2024-03-27 083205](https://github.com/Tanay03Trivedi/VPC-Peering-connection/assets/160705084/524dd3d9-fada-45f4-b9b8-0f13ac3e7f21)

## Go to the second account and accept the peering request

![Screenshot 2024-03-27 083246](https://github.com/Tanay03Trivedi/VPC-Peering-connection/assets/160705084/4e5e3020-6f05-4e9d-9510-d8e3c10f17f1)

### then the status will be as shown active

![Screenshot 2024-03-27 083315](https://github.com/Tanay03Trivedi/VPC-Peering-connection/assets/160705084/64cbbdc4-954c-4ec5-812c-fbe600d90348)

![Screenshot 2024-03-27 083327](https://github.com/Tanay03Trivedi/VPC-Peering-connection/assets/160705084/d2fa2580-f222-4971-8d59-23ce69802558)

## Edit the route as per your IP as shown below on both vpc

![Screenshot 2024-03-27 083434](https://github.com/Tanay03Trivedi/VPC-Peering-connection/assets/160705084/8d72ec76-e458-4e7a-bc82-f6feb2f8aa14)

![Screenshot 2024-03-27 083524](https://github.com/Tanay03Trivedi/VPC-Peering-connection/assets/160705084/b686da83-17e9-4176-81d7-420f24b85669)

## Try ping to private IP again connection should be established

![Screenshot 2024-03-27 083624](https://github.com/Tanay03Trivedi/VPC-Peering-connection/assets/160705084/d6c151d2-0820-4f37-b7ad-d502b6da9d49)


![Screenshot 2024-03-27 083633](https://github.com/Tanay03Trivedi/VPC-Peering-connection/assets/160705084/a3fd85f7-19fb-4fb1-af2f-add6dc94502c)

