FROM python:3.8.7

RUN pip install neo4j requests beautifulsoup4

ADD ./wikiCrawler.py /opt/wikiCrawler.py

CMD ["python3","/opt/wikiCrawler.py","Philosophy"]