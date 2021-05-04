FROM fabric8/s2i-java:2.3
ENV AB_PROMETHEUS_OFF=true JAVA_APP_DIR=/deployments
LABEL org.label-schema.description="Hello microservice using Thorntail" org.label-schema.version=1.0 org.label-schema.schema-version=1.0 org.label-schema.build-date=2021-04-19T11:49:42.186 org.label-schema.name="Red Hat Training Hello Java app" org.label-schema.vcs-ref=f82582c8ecb2d4bd3670252f287cc9e2d1f25fd0 org.label-schema.vcs-url=git@github.com:rumyesHo/DO288-apps.git
EXPOSE 8080 8778 9779
COPY maven /deployments/
