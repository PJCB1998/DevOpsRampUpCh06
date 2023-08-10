# DevOpsRampUp Chapter 6
 
## VMs

    1) auth_api
        - AUTH_API_PORT=8000
        - AUTH_API_ADDRESS=http://192.168.56.20:8000
    2) users_api
        - SERVER_PORT=8083
        - USERS_API_ADDRESS=http://192.168.56.30:8083
    3) todo_api
        - TODO_API_PORT=8082
        - TODO_API_ADDRESS=http://192.168.56.40:8082
    4) lmp 
        - LMP_ADDRESS=http://192.168.56.50
    5) frontend
        - PORT=8080
        - FRONTEND_ADDRESS=http://192.168.56.60:8080
    6) db
        - REDIS_PORT=6379
        - REDIS_HOST=192.168.56.70
        - REDIS_CHANNEL=log_channel
    7) zipkin
        - ZIPKIN_PORT=9411
        - ZIPKIN_ADDRESS=http://192.168.56.80:9411
        - ZIPKIN_URL=http://192.168.56.80:9411/api/v2/spans


