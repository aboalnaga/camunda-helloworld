FROM eruvanos/xvfb

LABEL maintainer="Ebrahim Aboalnaga <contact@aboalnaga.com>"
LABEL version="1.0"

RUN curl https://downloads.camunda.cloud/release/camunda-modeler/4.7.0/camunda-modeler-4.7.0-linux-x64.tar.gz \
  -Lo camunda-modeler-4.7.0-linux-x64.tar.gz
RUN tar xzf camunda-modeler-4.7.0-linux-x64.tar.gz
RUN rm -f camunda-modeler-4.7.0-linux-x64.tar.gz
RUN mv camunda-modeler-4.7.0-linux-x64 camunda-modeler
CMD /camunda-modeler/camunda-modeler --no-sandbox
