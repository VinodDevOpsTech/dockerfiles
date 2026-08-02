ARG version
FROM almalinux:${version-9}
ARG course="docker" \
    std-name="vinod" \
    duration="10hrs"
ENV course=${course} \
    name=${std-name} \
    Duration=${duration}
RUN echo "Course is: ${course}, name: ${std-name}, duration: ${duration}"
CMD ["sleep", "100"]