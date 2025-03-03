FROM almalinux:9
ENV course="Devops with aws"
ENV trainer="shiva"
#here user1 is key, someuser is default value
ARG ${username:-someuser}
RUN echo "Hello User :${username}" 
CMD ["sleep", "100"]