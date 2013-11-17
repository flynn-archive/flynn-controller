# Flynn API

The Flynn HTTP API server allows for finding which jobs are running, scheduling
new jobs, and getting job logs. When scheduling a job, it gets the current
cluster state from [sampie](https://github.com/flynn/sampi), decides where to
run the job, and then communicates the scheduling request back to sampi.

## TODO

- Implement robust host failure logic
