# JMeter Performance Testing Project

## Overview

This project demonstrates performance testing using Apache JMeter. It focuses on designing workload scenarios, executing HTTP requests, collecting performance metrics, and analyzing test results.

The project provides practical experience with performance testing concepts, including virtual users, ramp-up periods, response times, throughput, error rates, and performance reports.

## Technologies Used

* **Apache JMeter** — Performance and load testing
* **HTTP** — Web request testing
* **CSV** — Test data parameterization
* **Git and GitHub** — Version control and project hosting

## Key Features

* HTTP request performance testing
* Virtual user configuration
* Ramp-up and loop-count configuration
* Workload modeling
* Parameterization using CSV test data
* Response-time analysis
* Throughput monitoring
* Error-rate analysis
* Percentile analysis, including P50, P90, P95, and P99
* Performance test result collection and reporting

## Performance Testing Concepts

### Load Testing

Evaluates application behavior under an expected workload.

### Stress Testing

Examines system behavior as workload increases beyond normal operating conditions.

### Spike Testing

Evaluates how the system responds to sudden increases or decreases in workload.

### Endurance Testing

Examines system behavior under sustained load over an extended period.

### Volume Testing

Evaluates system behavior when handling large amounts of data.

## Project Files

The repository includes the JMeter test plan and supporting test data and result files.

* **JMeter test plan (`.jmx`)** — Defines the performance test configuration and execution flow.
* **CSV test data** — Supports parameterized test requests.
* **Result files** — May be used for performance analysis and reporting.

## Prerequisites

Before running the project, install:

1. Apache JMeter
2. Git, if you want to clone the repository
3. A Java runtime supported by your installed JMeter version

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/vishnusaichellam/SDET-Performance-Test.git
```

### 2. Open the Test Plan

Open Apache JMeter and load the `.jmx` test plan from the cloned repository.

### 3. Review the Configuration

Before execution, review the Thread Group settings, HTTP requests, test data paths, timers, assertions, and listeners.

Update any local file paths or environment-specific values if necessary.

### 4. Execute the Test

Run the test plan in Apache JMeter's GUI for learning and troubleshooting.

For larger performance tests, use non-GUI execution where appropriate.

Example:

```bash
jmeter -n -t "SDET Performance Test.jmx" -l results.jtl
```

The command assumes that JMeter is available on your system path and that the test plan is located in the current directory.

## Metrics to Analyze

When reviewing a performance test, consider:

* **Response Time** — Time taken to receive a response
* **Latency** — Time until the response begins
* **Throughput** — Number of requests processed per unit of time
* **Error Rate** — Percentage of failed requests
* **Percentiles** — Response-time distribution, including P90, P95, and P99
* **Connect Time** — Time required to establish a connection

Interpret these metrics together with the workload, test duration, environment, and application requirements.

## Skills Demonstrated

* Apache JMeter test-plan design
* Performance workload modeling
* HTTP request testing
* Test-data parameterization
* Performance metrics analysis
* Response-time percentile analysis
* Test execution and result collection
* Performance testing fundamentals
* Git and GitHub

## Future Improvements

Potential improvements include:

* Generating HTML performance dashboards
* Automating test execution through Maven
* Integrating performance tests into CI/CD pipelines
* Adding performance thresholds and automated validation
* Documenting test environment details and workload assumptions

## Author

**GitHub:** [vishnusaichellam](https://github.com/vishnusaichellam)
