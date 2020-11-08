# MovieCatalogApplication- SpringBoot Microservices Project

1. movie-catalog-service -> Main Service of application which consumming movie-info-service and ratings-data-service using SprintBoot RestTemplate. 
   
2. movie-info-service -> RestAPI which use as to provide movies inforamation
  
3. ratings-data-service -> RestAPI which use as to provide movives ratings
  
4. discovery-server -> discover-server(Eureka server) is act as application which holds the information of all three client services (movie-catalog, movie-info-service & ratins-data-service). All three Micro services has registred into the Eureka server and Eureka server knows all the client applications running on which port and IP address.
