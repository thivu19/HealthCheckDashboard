# HealthCheckDashboard

The goal of this exercise is to create a live health check dashboard for the JobTread API. The dashboard should show the API version and a bar chart of the last 10 response times (in milliseconds) of simple GET requests to https://api.jobtread.com/healthz, updated every second.

For example (not to scale):

          JobTread API Version abc123

               ---- ---- ----      ----
     ----      ---- ---- ---- ---- ----      ----
---- ---- ---- ---- ---- ---- ---- ---- ---- ----
---- ---- ---- ---- ---- ---- ---- ---- ---- ----
---- ---- ---- ---- ---- ---- ---- ---- ---- ----
---- ---- ---- ---- ---- ---- ---- ---- ---- ----
22.1 23.3 22.2 25.3 26.7 26.5 23.9 26.3 22.2 23.3

## Requirements:
- Render your root component to the `root` <div> provided below.
- No external CSS or JavaScript should be imported besides the React and
  ReactDOM libraries already included below.
- Include all of your CSS and JavaScript in this file in the <style> and
  <script> tags below.
- The entirety of the completed exercise should be contained in this file.
- The dashboard should run correctly in the latest version of Chrome when served
  from the file protocol. Other browsers do not need to be tested for this
  exercise.
- The dashboard should be responsive to different screen widths.
- Feel free to present the data in additional ways as well, if you choose.
- Your submission will be evaluated on both visual design and code quality.
