FROM python:3
WORKDIR /home/haresh/Image-Classification
COPY requirments.txt ./
RUN pip install --no-cache-dir -r requirments.txt
COPY . .
RUN pip install ./en_core_web_sm-2.0.0.tar.gz
CMD ["python,"app.py"]