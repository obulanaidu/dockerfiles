ARG version
FROM almalinux:${version:-9}
ENV course="devops" \
    duration="120HRS" 
ARG trainer="obulanaidu"
ENV trainer=$trainer
RUN echo "hello my course is ${course},${duration},${trainer}"
CMD ["sleep", "1000"]  
