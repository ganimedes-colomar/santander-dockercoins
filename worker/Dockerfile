FROM python
RUN pip install redis && pip install requests
COPY worker.py .

ENTRYPOINT ["python"]
CMD ["worker.py"]
