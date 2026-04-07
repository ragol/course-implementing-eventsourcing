
## Understanding Eventsourcing - Online Course

Learn the concepts of Event Modeling & Event Sourcing with a consistent example from rough requirements to running code. 

This is the companion online course to the [Understanding Eventsourcing](https://github.com/dilgerma/course-implementing-eventsourcing) Book.

Get it here: 
[Course Implementing Eventsourcing](https://www.eventsourcingcourse.com)

install via
```
npm install
```

run via

```
npm run dev
```

access via
```
localhost:3000
```

## Running the stack

I use podman to run the stack. You can use docker or docker-compose. The commands are the same. Just replace `podman` with `docker` or `docker-compose`.

Use compose.yaml to run the whole stack:
```
podman compose up
```
and code generator:
```
podman compose --profile tools up -d codegen
podman compose exec codegen bash
```
Replace `bash` with the specific command you want to run.
