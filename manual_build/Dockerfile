FROM python
WORKDIR /app
COPY hello.py .
COPY start_app.sh .
RUN pip install Flask
CMD ["/bin/bash", "start_app.sh"]