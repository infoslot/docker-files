FROM kalilinux/kali-rolling
ENV DEBIAN_FRONTEND=noninteractive
RUN apt update && apt -y install kali-linux-headless
VOLUME kali-volume:/app/data
WORKDIR /root
RUN git clone https://github.com/danielmiessler/SecLists.git
RUN apt -y install sublist3r 
