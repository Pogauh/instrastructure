FROM apache/hop:2.7.0

COPY ./hop-project /project

WORKDIR /project

CMD ["hop-run.sh", "-p", "pandemie", "-f", "pipelines/pipeline1.hpl", "-e", "dev"]
