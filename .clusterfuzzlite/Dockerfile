FROM gcr.io/oss-fuzz-base/base-builder-go@sha256:d30c99740f50343c0a58c2f32b2e519a40172c80816e48d45bcc5232cbd8a6e0
COPY . $SRC/atlantis
COPY .clusterfuzzlite/build.sh $SRC/build.sh
WORKDIR $SRC/atlantis
