# syntax=docker/dockerfile:1
FROM varnish:7.4

LABEL maintainer="Érico Andrei <ericof@plone.org>" \
      org.label-schema.name="trepr-varnish" \
      org.label-schema.description="Treinamento TRE-PR Varnish image." \
      org.label-schema.vendor="Érico Andrei"

COPY etc/varnish.vcl /etc/varnish/default.vcl
