# NATS Stream

## Prerequisites

This command need the [NatsCLI tools](https://github.com/nats-io/natscli?tab=readme-ov-file)

## Commands

### Connect to NATS serveur with user

```shell
nats context add secured \
  --server nats://localhost:4222 \
  --user monuser \
  --password monmotdepasse
```

### Connect with credentials

```shell
nats --creds ../../Users/cofie/Downloads/corentin.fievet.staging.creds consumer ls --server=nats://nats.mnq.fr-par.scaleway.com:4222
```

### Get the stream list

```shell
nats stream ls
```

### Create a new stream

```shell
nats stream add <stream-name> \
  --subjects "<stream-start>.>" \
  --storage file \
  --retention limits \
  --max-msgs 1000 \
  --max-bytes 10MB \
  --max-age 1h
```

### Get the steam info

```shell
nats stream info <stream-name>
```

### Get the stream messages

```shell
nats stream view messages
```

### Published message in subject

```shell
nats pub <subject> "hello"
```

### Delete stream

```shell
nats stream rm <stream-name>
```
