# Investigating Disk Scheduling Performance

A responsive, interactive Operating Systems mini project that demonstrates and compares six disk scheduling algorithms.

## Overview

This website helps students understand how an operating system services pending disk I/O requests. Enter a request queue and starting head position to simulate the algorithms and compare their total head movement.

## Algorithms Included

- **FCFS** — First Come First Serve
- **SSTF** — Shortest Seek Time First
- **SCAN** — Elevator Algorithm
- **C-SCAN** — Circular SCAN
- **LOOK**
- **C-LOOK**

## Features

- Interactive disk scheduling simulation
- Custom request queue, starting head position, cylinder range, and direction
- Seek sequence and total head movement results
- Performance comparison table for all six algorithms
- Bar chart and seek-sequence line chart
- Best-performing algorithm identification for the entered data
- Sample data, reset, and clear controls
- Dark/light theme toggle
- Responsive layout for desktop and mobile

## Technologies Used

- HTML5
- CSS3
- JavaScript
- [Chart.js 4.4.1](https://www.chartjs.org/) for charts (loaded from a CDN)

## How to Run

1. Download or clone this repository.
2. Open `index.html` in a web browser.
3. Enter disk requests separated by commas or spaces.
4. Set the starting head position, minimum and maximum cylinder values, and movement direction.
5. Click **Run Simulation** to view the results.

> An internet connection is required to load Chart.js from its CDN and display the charts.

## Sample Input

The website starts with this sample data:

- Request queue: `98, 183, 37, 122, 14, 124, 65, 67`
- Starting head position: `53`
- Minimum cylinder: `0`
- Maximum cylinder: `199`
- Direction: `Towards higher (right)`

Use **Load Sample** to restore these values.

## Project Structure

```text
disk-scheduling-performance/
├── index.html
└── README.md
```

## Learning Objectives

- Understand how disk scheduling works.
- Study the seek sequence produced by different algorithms.
- Calculate and compare total head movement.
- Observe how the request queue and initial head position affect performance.

## Note

The results are based on the input values and the movement rules implemented in this educational simulator. The algorithm with the lowest total head movement for one input is not necessarily the best choice for every workload.

## Author

Add your name, department, college, and academic year here.

## License

This project is intended for educational use. Add a license file if you want to specify reuse and distribution terms.
