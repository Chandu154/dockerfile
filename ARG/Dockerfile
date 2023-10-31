ARG version
FROM almalinux:${version:-8}
#ARG variable before FROM will not work after FROM 
RUN echo "version passed by the user is: ${version}"
ARG COURSE
ARG TRAINER
RUN echo "Course is: ${COURSE} and Trainer is: ${TRAINER} "