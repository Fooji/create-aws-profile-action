# Create AWS profile action

A GitHub action to setup an AWS profile on the file system.

## Inputs

### `key`

**Required** The AWS key

### `secret`

**Required** The AWS secret

### `region`

**Required** The AWS region

### `profile`

**Required** The name of the profile you want to create

### `sessionToken`

**Not required** The AWS session token

## Example usage

```
uses: Fooji/create-aws-profile-action@v1
with:
  profile: staging
  region: us-west-1
  key: xxx
  secret: xxx
  sessionToken: xxx
```