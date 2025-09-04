# Error “Maximum number of comments exceeded”

```text
Some the CI pipelines in GitLab are failing with error `400 Bad request "Maximum number of comments exceeded"`.

How many comments can be added to a single MR in GitLab? #context7
```

```text
Generate a Bash script to check the number of notes for MRs.

Use the MR linked below to test it. The expected result is **238** comments.

https://code.roche.com/galileo-genai/rochechat/azure-iac/-/merge_requests/284

Use the GitLab API #context7. There is an environment variable `GITLAB_GRZENKOM_READ_TOKEN`
that should be used for authentication.

API endpoint: https://code.roche.com/api/v4/
```