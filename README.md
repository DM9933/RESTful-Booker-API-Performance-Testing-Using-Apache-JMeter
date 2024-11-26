# RESTful Booker API Performance Testing Using Apache JMeter

This repository demonstrates how performance testing was conducted on the RESTful Booker API using Apache JMeter. The tests include scenarios like stress, spike, and endurance testing.

## Introduction

The RESTful Booker API was tested to assess its responsiveness, scalability, and reliability under varying loads. The results identify bottlenecks and provide optimization recommendations.

## Features
- Load testing with Apache JMeter
- Stress testing to evaluate system limits
- Spike testing to measure response to sudden traffic surges
- Endurance testing for prolonged periods to assess reliability

## Results Summary
### Performance Metrics
| **Users** | **Avg. Response Time (ms)** | **90th Percentile (ms)** | **Max Response Time (ms)** | **Error Rate** |
|-----------|-----------------------------|--------------------------|----------------------------|----------------|
| **100**   | 402.42                      | 1141.90                 | 1773.00                    | 0.00%          |
| **400**   | 551.80                      | 1340.90                 | 9878.00                    | 0.00%          |
| **800**   | 1280.42                     | 3550.00                 | 24500.00                   | 0.16%          |

## Tools Used
- **Apache JMeter**: For simulating traffic and analyzing performance metrics.
- **RESTful Booker API**: The system under test (SUT).

## Setup and Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/DM9933/RESTful-Booker-API-Performance-Testing-Using-Apache-JMeter.git
