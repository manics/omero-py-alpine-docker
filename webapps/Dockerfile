FROM omero-py-alpine/omero-web:latest
MAINTAINER spli@dundee.ac.uk

USER root
RUN apk --no-cache add \
        # omero-figure \
        py-reportlab \
        py-markdown \
        # omero-mapr \
        py-requests && \
    pip install \
        omero-figure \
        omero-fpbioimage \
        omero-iviewer \
        omero-mapr \
        omero-parade

USER omero
