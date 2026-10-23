# Build, Run, and Test Checklist

This is a checklist template. Replace commands with the commands that work for your actual repository.

## Before build
- [ ] Confirm Python and OpenCV 5 compatibility in the target environment.
- [ ] Pin dependencies in a requirements/lock file.
- [ ] Add `.env.example` containing names of required variables, never real secrets.
- [ ] Add test images/videos and document their source and usage permissions.
- [ ] Ensure the core workload genuinely uses OpenCV 5.

## Local run
1. Create and activate a virtual environment.
2. Install pinned dependencies.
3. Configure required environment variables.
4. Run the application using the verified command.
5. Open the local URL and test a normal case, a suspected defect, an ambiguous case, and an invalid input.

## Test evidence
- [ ] Record the exact dataset and test cases.
- [ ] Save annotated outputs and decision traces.
- [ ] Record precision, recall, false positives, and latency where appropriate.
- [ ] Document failure cases and limitations.
- [ ] Verify that a visual result changes a subsequent agent action.

## AWS deployment
- [ ] Deploy only after local tests pass.
- [ ] Use least-privilege IAM permissions.
- [ ] Do not commit AWS keys, tokens, or personal data.
- [ ] Add logs and basic error handling.
- [ ] Check costs and shut down unused resources.
- [ ] Verify the public demo URL or prepare a live screen-share demo.
