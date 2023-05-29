FROM python:latest

RUN curl -sSL https://install.python-poetry.org | POETRY_HOME=/etc/poetry python3 -
RUN echo 'export PATH="/etc/poetry/bin:$PATH"' >> /root/.bashrc
CMD ["python3"]
