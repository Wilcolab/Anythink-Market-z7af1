FROM python:3.9.13

RUN curl -sSL https://install.python-poetry.org | python - --version 1.2.0

ENV PATH="$PATH:/root/.local/bin"

# COPY pyproject.toml .
# COPY poetry.lock .

# RUN poetry install

# RUN poetry export -f "requirements.txt" --without-hashes --with-credentials > "requirements.txt"

ADD https://raw.githubusercontent.com/vishnubob/wait-for-it/master/wait-for-it.sh /wait-for-it.sh

RUN chmod +x /wait-for-it.sh
