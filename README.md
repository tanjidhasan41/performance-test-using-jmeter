# Project Description
This project implements performance and stress testing using Apache JMeter to evaluate the performance of two systems.

- booking API: Simulates user scenarios involving login, booking creation, and booking search under high load.
- dmoney API: Tests various transaction scenarios, including deposits, send money, and merchant payments.

# Prerequisites
- Apache JMeter
- Java Development Kit (JDK)

# What I Have Done
- booking API:
  - Configured API for login, booking creation, and booking search in Jmeter
  - Used a Gaussian Random Timer for simulating realistic user behavior
  - Conducted load tests with increasing durations (5, 10, and 20 minutes)
  - Conducted stress tests to identify the server's bottleneck throughput
  - Generated HTML and Excel reports for both load and stress tests

- dmoney API:
  - Set up scenarios for deposits, send money, and merchant payments
  - Used dynamic data from CSV files to simulate real-life transactions
  - Added assertions to ensure transaction success
  - Created a multi-threaded environment with a ramp-up period for realistic simulation

# How to Run the Tests
- Download and install Apache JMeter
- Ensure JDK is installed
- Place the ```.jmx``` files and ```.csv``` files in a dedicated directory
- Open the ```.jmx``` files in JMeter

**For booking API**
- Ensure the URLs are accessible
- Review and configure the random data generators for booking details

**For dmoney API**
- Fill ```deposit.csv```, ```sendMoney.csv```, and ```payment.csv``` with test data
- Configure the token in the Header Manager for authorization

**Run**
- Launch Apache JMeter
- Open ```booking.jmx``` or ```dmoney.jmx```
- Run the test plan by clicking the Start button
- Monitor test progress in the View Results Tree or Summary Report
- Save the results as an HTML report

# Reports for Task-1
**Load Test HTML Report**

![image](https://github.com/user-attachments/assets/62e78b2c-111f-4222-9356-c028209a4c5d)

**Load Test Excel Report**

![image](https://github.com/user-attachments/assets/bff9e9cd-2043-4786-bb30-56ce988f7074)

**Stress Test HTML Report**

![image](https://github.com/user-attachments/assets/dd912f75-7231-4727-8e32-e2e804037613)

**Stress Test Excel Report**

![image](https://github.com/user-attachments/assets/97b03368-da27-4d37-b435-be41403603bb)

# Report for Task-2

![image](https://github.com/user-attachments/assets/96c4132d-a176-4aa2-a386-8665236af193)
