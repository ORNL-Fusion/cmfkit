
FROM ubuntu:22.04

RUN set -x \
  && apt-get update \
  && DEBIAN_FRONTEND=noninteractive \
     apt-get install -y --no-install-recommends tzdata \
  && apt-get install -y \
                gfortran \
                libnetcdf-dev \
                libnetcdff-dev \
                cmake

