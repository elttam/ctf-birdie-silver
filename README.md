# Overview

Hack the container until you recover the flag.

**Title:** Birdie Silver  
**Category:** Crypto  
**Flag:** `libctf{42df98fb-3676-45bb-8dd0-faaed04c7cee}`  
**Difficulty:** Medium

# Usage

The following will pull the latest 'elttam/ctf-birdie-silver' image from DockerHub, run a new container named 'libctfso-birdie-silver', and publish the vulnerable service on port 80:

```sh
docker run --rm \
  --publish 80:80 \
  --name libctfso-birdie-silver \
  elttam/ctf-birdie-silver:latest
```

# Build (Optional)

If you prefer to build the 'elttam/ctf-birdie-silver' image yourself you can do so first with:

```sh
docker build ${PWD} \
  --tag elttam/ctf-birdie-silver:latest
```
