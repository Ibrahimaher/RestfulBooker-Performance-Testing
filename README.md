# Restful Booker - Performance Testing

## Overview
Performance testing for the Restful Booker API using Apache JMeter 5.6.2, covering full CRUD operations with dynamic data extraction and detailed performance reporting.

## Test Plan Structure
| Request | Description |
|---------|-------------|
| HTTP auth Request | Token-based authentication |
| HTTP get books Request | Retrieve all bookings |
| HTTP get bookid Request | Retrieve booking by ID |
| HTTP create bookid Request | Create new booking |
| HTTP update bookid Request | Full update (PUT) |
| HTTP delete bookid Request | Delete booking |

## Tools & Components
| Component | Details |
|-----------|---------|
| Tool | Apache JMeter 5.6.2 |
| Extractors | JSON Extractor, Boundary Extractor |
| Assertions | Response Assertion |
| Reports | Summary Report, Aggregate Report |

## API Under Test
- **API:** Restful Booker
- **URL:** https://restful-booker.herokuapp.com
- **Methods Tested:** GET, POST, PUT, DELETE

## How to Run
1. Install Apache JMeter 5.6.2
2. Open `RestfulBooker-PerformanceTest.jmx`
3. Click the **Run** button ▶
4. View results in **Summary Report** or **Aggregate Report**
