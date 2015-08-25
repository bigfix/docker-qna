A collection of Dockerfiles with IBM BigFix QnA

# Usage
## Prerequisites
- [docker](https://docs.docker.com/installation)

## Example
The following example creates a 9.2.5.130 QnA image on CentOS 7:

```bash
docker build -t bigfix/qna-centos:9.2.5 .
docker run -t -i bigfix/qna-centos:9.2.5
BESClientActionMastheadPath not set and no masthead found
Q: name of operating system
A: Linux CentOS 7.1.1503
T: 208
```

# Support
Any issues or questions regarding this software should be filed via [GitHub issues](https://github.com/bigfix/docker-qna/issues).
