## warehouse_config.cfg file in warehouse folder contains  

    [AWS]  
    KEY=<AWS-KEY>
    SECRET=<AWS-SECRET-KEY>
      
    [CLUSTER]  
    HOST='<Redshift Cluster Endpoint>'  
    DB_NAME='<db-name>'  
    DB_USER='<db-user-name>'  
    DB_PASSWORD='<db-password>'  
    DB_PORT=<db-port, default 5439>  
      
    [IAM_ROLE]  
    ARN=<Redshift ARN role>
      
      
    [STAGING]  
    SCHEMA=<Warehouse-staging-schema>  
      
    [WAREHOUSE]  
    SCHEMA=<Warehouse-schema>  
      
      
    [BUCKET]  
    LANDING_ZONE=<landing-zone-bucket>  
    WORKING_ZONE=<working-zone-bucket>
    PROCESSED_ZONE=<processed-zone-bucket>

---

## Maintainer

Madhav Meesala
Software Engineer
Email: madhavmeesala@gmail.com

About the Developer
Madhav is a Software Engineer with over 4 years of experience building scalable full-stack and distributed systems. He specializes in cloud-native development, AWS infrastructure, and database optimization, focusing on delivering high-performance solutions for complex data environments.