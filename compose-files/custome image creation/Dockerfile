FROM drupal:8.6

RUN apt-get update && apt-get install git \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /var/www/html/thems

RUN git clone --branch 8.x-3.x --single-branch -depth 1 https://git.drupalcode.org/project/drupal.git

