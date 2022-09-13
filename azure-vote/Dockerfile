FROM tiangolo/uwsgi-nginx-flask:python3.6
RUN usermod -aG docker jenkins
RUN pip install redis
ADD /azure-vote /app
