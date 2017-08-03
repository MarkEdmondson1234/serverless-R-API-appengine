FROM gcr.io/gcer-public/plumber-appengine
LABEL maintainer="mark"
# RUN export DEBIAN_FRONTEND=noninteractive; apt-get -y update \
# && apt-get install -y 
 
# RUN ["install2.r", "-r 'https://cloud.r-project.org'", ""]
# RUN ["installGithub.r", ""]

WORKDIR /payload/
COPY [".", "./"]

CMD ["api.R"]