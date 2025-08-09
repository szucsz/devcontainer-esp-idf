FROM espressif/idf:v5.5
# Install and configure locales for UTF-8 support
RUN apt-get update && \
    apt-get install -y locales && \
    locale-gen en_US.UTF-8 && \
    echo "export LANG=en_US.UTF-8" >> /root/.bashrc && \
    echo "export LC_ALL=en_US.UTF-8" >> /root/.bashrc
RUN echo "source /opt/esp/idf/export.sh" >> /root/.bashrc
