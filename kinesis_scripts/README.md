# Kinesis Scripts

Scripts can be placed here to stream data records over to a Kinesis stream, with the intention of being able to consume 
shards with Lambda.

## Prerequisites

- Python 3.X
- Pipenv (pip install --user pipenv)

## Usage

```bash
$ pipenv install
$ pipenv run python3 SCRIPT.py
```

## Resources

https://docs.aws.amazon.com/lambda/latest/dg/with-kinesis-example.html