# sample-html-docker-application
git clone https://github.com/sathish-sempublingam/sample-html-app.git
cd  sample-html-docker-application

mvn clean install

docker build -t html-application  .

docker run -d -p 80:80 html-application

docker ps 
