FROM almalinux
RUN dnf install angix -y
# root access required to create user or install packages
RUN useradd roboshop
USER roboshop
CMD ["sleep","100"]
