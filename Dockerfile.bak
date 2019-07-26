FROM python:alpine
RUN pip install flask -i https://pypi.douban.com/simple
ADD app.py ./
EXPOSE 5000
CMD ["python", "app.py"]
