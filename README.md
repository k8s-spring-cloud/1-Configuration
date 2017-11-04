# 1-Configuration
Repository for all service configuration files utilized by Spring Cloud Config for this starter project.

## Software Infrastructure
Within this section you'll find all infromation neccessary to understand the cross-cutting components utilized by this project.  For any service hosted inside of the K8s cluster, I've implemented the following naming convention: wb3-k8s-[Description].

### Resource URIs
* Spring Cloud | Configuration Server
  * Cluster URI : http://service-discovery.default.svc.cluster.local/eureka/
  * Git: https://github.com/k8s-spring-cloud/config-server
  * Docker Image: https://hub.docker.com/r/k8springcloud/config-server/
* Spring Cloud | NetFlix OSS - Eureka Service Discovery Server
  * Cluster URI : https://service-discovery.default.svc.cluster.local/eureka/
  * Git: https://github.com/k8s-spring-cloud/service-discovery
  * Docker Image: https://hub.docker.com/r/k8springcloud/service-discovery/
* Spring Cloud | NetFlix OSS - Zuul Edge Server
  * Cluster URI : https://edge-gateway.default.svc.cluster.local/eureka/
  * Git: https://github.com/k8s-spring-cloud/edge-gateway
  * Docker Image: https://hub.docker.com/r/k8springcloud/edge-gateway/
  
  
  
## Software Servies
These are links and information about the sample micro-services being utilized for this project.

### Resource URIs
* Hello World
  * Cluster URI : https://hello-world.svc.cluster.local
  * Git: [In work]
