FROM ghcr.io/containerbase/gitpod:11.6.6

# renovate: datasource=pypi
RUN install-tool poetry 1.8.3

# https://github.com/parcel-bundler/parcel/issues/6569
ENV PARCEL_WORKER_BACKEND=process
