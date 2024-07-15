FROM python:3.9-slim
ARG nomeApp
ENV nomeAppRun=${nomeApp}
WORKDIR /app
ADD ${nomeApp}.py .
CMD python ${nomeAppRun}.py
