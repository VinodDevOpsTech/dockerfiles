ARG version
FROM almalinux:${version-9}
ARG course="docker" \
    stdname="vinod" \
    duration="10hrs"
ENV course=${course} \
    stdname=${stdname} \
    duration=${duration}
RUN echo "Course is: ${course}, name: ${stdname}, duration: ${duration}"
CMD ["sleep", "100"]