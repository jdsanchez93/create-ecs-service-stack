# create-ecs-service-stack

To deploy the stack:
`sam deploy --guided --profile <profile>`

For example:
`sam deploy --guided --profile create-ecs-service-stack --config-env webcam-image-viewer-prod`

Prerequisites

1. Ensure docker image exists
2. Create ECS Task Definition in aws
3. Build & deploy this stack