FROM python:3.9

WORKDIR /app 
COPY requirement.txt ./
RUN pip install -r requirement.txt
COPY ./ ./cli
COPY ./cli.sh /bin/actions
CMD ["tail","-f","/dev/null"]
