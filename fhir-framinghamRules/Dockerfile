FROM registry.access.redhat.com/jboss-decisionserver-6/decisionserver64-openshift:latest

COPY target/fhir-framinghamRules-1.0-SNAPSHOT.jar $JBOSS_HOME/standalone/deployments
RUN /usr/local/s2i/assemble
