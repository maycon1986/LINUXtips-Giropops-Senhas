FROM python:slim
WORKDIR /app
COPY . ./
RUN pip install --no-cache-dir -r requirements.txt
EXPOSE 5000
ENTRYPOINT ["flask", "run", "--host=0.0.0.0" ]