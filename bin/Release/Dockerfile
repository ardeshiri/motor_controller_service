FROM ubuntu:20.04
COPY ./motor_ctrl_service /
RUN apt-get update
RUN apt-get install -y libssl-dev
RUN apt-get install -y librabbitmq-dev
ENTRYPOINT ["/motor_ctrl_service"]
