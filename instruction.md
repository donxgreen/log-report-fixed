An Apache-style access log is available at:

/app/access.log

Analyze the log and create:

/app/report.json

The output must be valid JSON and contain exactly the following fields:

1. total_requests
   - The total number of log entries in the access log.

2. unique_ips
   - The number of unique client IP addresses that appear in the access log.

3. top_path
   - The request path that appears most frequently in the access log.

The verifier will check all three values.

You have 120 seconds to complete this task. Do not cheat by using online solutions or hints specific to this task.
