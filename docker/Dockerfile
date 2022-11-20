FROM python
RUN pip install -U Flask redis
RUN useradd -ms /bin/bash admin
USER admin
WORKDIR /app
COPY app /app
CMD ["python","app.py"]
