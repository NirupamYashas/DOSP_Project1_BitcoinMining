## Distributed Operating System Principles
## Project 1 : Bitcoin Mining Using Actor model in Erlang

### Group Members
| Names | UF-ID |
| ------ | ------ |
| Vamsi Pachamatla | 1708-0059 |
| Yashas Kuchimanchi | 5043-1189 |

## Overview



## Instructions to run the code

#### 1. Server and Client are on Different Systems

#### 2. Server and Client are executed in the Same System 


## 
## 1. Size of the Work Unit for 4 leading zeros

| Actors | Ratio( CPU time / Realtime) - 3 Leading Zeros | Ratio( CPU time / Realtime) - 4 Leading Zeros |
| ------ | ------ | ------ |
| 4 | 1.625 | 2.22672 |
| 5 | 2.27 | 2.13895 |
| 10 | 4.9 | 3.00313 |
| 100 | 6.49857 | 5.63650 |
| 500 | 5.87721 | 5.77696 |
| 1000 | 6.59783 | 5.86406  |

## 2. Result for running the program on Input: 4

- The CPU to Real-time ratio for four leading zeroes with 100 workers is 5.63650, the ratio for 500 workers is 5.77696, and the ratio for 1000 workers is 5.86406. The utilization of the cores keeps on increasing when we increase the cores.
#### 100 workers with 4 leading zeroes
<img width="1440" alt="4 leading zeroes and 100 Bitcoins" src="https://user-images.githubusercontent.com/48962308/192126428-b197d80e-ab0a-4dfa-87fd-71f174213c59.png">

#### 500 workers with 4 leading zeroes
<img width="1438" alt="4 leading zeroes and 500 Bitcoins" src="https://user-images.githubusercontent.com/48962308/192126431-bd7c43b7-a615-4c03-bde6-0748b494e39d.png">

#### 1000 workers with 4 leading zeroes
<img width="1439" alt="4 leading zeroes and 1000 Bitcoins" src="https://user-images.githubusercontent.com/48962308/192126433-f81b26e0-5425-42a6-9250-30ebc20f0f96.png">


## 3. The coin with the most 0s you managed to find
- We managed to find 2 coins with 6 Leading Zeros with 1.81986 cpu time to real-time ratio 
<img width="1438" alt="6 leading zeroes and 2 workers" src="https://user-images.githubusercontent.com/48962308/192126342-19974a04-26f7-4265-aeee-338aa9e729df.png">

## 4. The largest number of working machines you were able to run your code with.
