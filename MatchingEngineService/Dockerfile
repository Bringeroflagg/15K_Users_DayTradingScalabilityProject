FROM python:3.11-slim
WORKDIR /app
COPY . /app
RUN pip install flask pymongo python-dotenv flask-cors 
COPY MatchingEngineService /app
RUN pip install flask pyjwt redis
EXPOSE 5300
CMD ["python", "matching_engine_service.py"]
