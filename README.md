# Logging with ElasticSearch 7.6.2, Kibana, .NET Core 3.1 and Serilog

## Steps To Run the Solution:
* Run the Elasticsearch and Kibana containers in Docker
    * cd src
    * docker-compose up -d
    * Wait for Elastic and Kibana to start up 

* Run the netcore application (Using Visual Studio)
    * Open the solution file at 'src/Elastic.Serilog.Web.sln'
    * Hit F5 to build and launch the site
    * A new browser window will open with the url http://localhost:5000
    
* View Kibana logs at http://localhost:5601
