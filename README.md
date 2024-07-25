# TrafficLightController
 
The purpose of this project is to design a methodology using Verilog to control the traffic with specified time delays for a T-Shaped road.

## Methodology

### Directions Considered

![directions](https://user-images.githubusercontent.com/83152452/131366734-67c76e3c-b53d-49ca-a5ba-fb058d19d578.png)

The directions, M1, MT, M2, S, that is been considered for analysis of our problem is shown in the figure. And, the problem statement is explained in the figure. 
Six states, S1, S2, S3, S4, S5, S6 are taken into consideration and state diagram, state table is made using the following logic explained in the figure. 
Time delays for changing from one state to another is considered as, TMG(from S1 to S2), TY(from S2 to S3), TTG(from S3 to S4), TY(from S4 to S5), TSG(from S5 to S6) 
and TY(from S6 to S1) and the cycle continues.

### Problem Statement

![Logic_Diagram](https://user-images.githubusercontent.com/83152452/131366783-8c025386-8011-4ef9-a766-d0a07e4244ac.png)

- Green light indicates that there is no traffic and there is easy flow of vehicles in that route/direction. 
- Red light indicates that there is a traffic jam and that route is blocked for the vehicles to move and, 
- Yellow light indicates that the route has medium flow of vehicles. 
