FROM almalinux:9
ENV course="Devops with aws"
ENV trainer="shiva"
#here user1 is key, someuser is default value
ARG ${username:-someuser}
RUN echo "Hello ${username}" > /tmp/devops.txt 
CMD ["sleep", "100"]