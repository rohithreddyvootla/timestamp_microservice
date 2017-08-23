# API BaseJump: Timestamp Microservice

# User Stories

1.I can pass a string as a parameter, and it will check to see whether that       string contains either a unix timestamp or a natural language date             (example: January 1, 2016).
2. If it does, it returns both the Unix timestamp and the natural language        form of that date.
3.If it does not contain a date or Unix timestamp, it returns null for those     properties.

# Example Usage

  https://oasis-handle.glitch.me/August%2023,%202017
  https://oasis-handle.glitch.me/1503483809

# Example Output

{"unix":1503446400,"natural":"August 23, 2017"}
{"unix":null,"natural":null}