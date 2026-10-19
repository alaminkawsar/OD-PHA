# Basics Question (gpt generated)
Generated your CSV file with 50 basic Samsung Health question–answer pairs using entirely synthetic demo data.

Samsung Health — Basic Q&A Benchmark

CSV file · 50 question–answer pairs · UTF-8

Includes case IDs and a synthetic-data label.

Download the CSV file

### What's included?

| Data category          | Example                                              |
| ---------------------- | ---------------------------------------------------- |
| Heart rate             | Average, resting, minimum, and maximum heart rate    |
| Activity               | Steps, walking distance, calories, and exercise      |
| Sleep                  | Duration, deep sleep, REM sleep, and wake periods    |
| Blood pressure         | Systolic, diastolic, and complete readings           |
| Other health metrics   | Blood oxygen, temperature, weight, BMI, and body fat |
| Hydration and workouts | Water intake, workout duration, and pace             |

### CSV structure

The file contains three columns for each test case:

* `case_id` — unique identifier, such as `BASIC-001`

* `data_type` — `demo_synthetic`

* `question` — the user's question

* `answer` — the expected answer

These are basic, single-question data retrieval tests, suitable for your first benchmark phase. The answers use illustrative values and do not represent actual Samsung Health records.

For the next 50 advanced questions, we can introduce multi-tool retrieval, date-range comparisons, trends, missing data, and calculations. That will help you evaluate not only answer generation but also your agent's query understanding and tool-selection capabilities.
