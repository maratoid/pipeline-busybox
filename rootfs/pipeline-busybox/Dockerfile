FROM busybox
LABEL authors="Marat Garafutdinov<maratoid@gmail.com>"

ARG TEST_ARG=SOME-DEFAULT

RUN ls

COPY scripts/dockerScript.sh /dockerScript.sh
RUN chmod +x dockerScript.sh
RUN /dockerScript.sh