# Overview


A P-{0,1,2} has occurred at work. Try these different things.

- [ ] Check the logs.
    - [ ] Does anything look suspicious? Can you find logs at the warning level.
    - [ ] Pin that current log and see if anything looks interesting around it.
    - [ ] Search the term similar to the incident that has occurred in general. Maybe the logs for that event have changed over time.
    - [ ] Can you narrow the error down to a specific pod?
    - [ ] What does the error message say?
        - [ ] HTTP Error?
            - [ ] What was the status code
            - [ ] What does that status code mean?
        - [ ] GRPC Error?
            - [ ] Which service is failing

- [ ] Make sure you have as much information as you need.
  - [ ] How was the incident reported?
- [ ] Can you replicate the problem?
    - [ ] locally
    - [ ] on staging
    - [ ] on production
    - [ ] by impersonating the user?

- [ ] Who has more insight about the issue?

