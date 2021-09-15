### Discovery Questions

Here are some questions I find helpful to think about to discovery requirements or dependencies in the process of building new back-end features or services.

These questions should be asked as early as possible as to minimize re-work.

- Does it require database changes?
- Does it require backfilling data that didn't exist prior to a certain date that the feature depends on?
- Does it require a new API endpoint or the modification of an existing one?
- Is there a rough idea of the API request payload? Required or optional attributes?
- Is there a rough idea of the API response payload?
- Performance concerns (slow queries, external service calls, payload size)
- Any inter-service calls expected?
- Any external service calls expected?
- Are there dependencies or pre-requisites that can be identified now? (e.g. data sources, API plumbing, account establishment)
- Can a trial or test account be used for a vetting process?
