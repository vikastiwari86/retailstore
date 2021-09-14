# Getting Started

### Reference Documentation
For further reference, please consider the following sections:

#Retail Store Application

We have used Springboot-Java 11 with  h2 database for this project,

We have implemented the following api end point:

Http Method - POST

Endpoint - localhost:8080/api/discounts


Example request:

"user": {
        "type": "EMPLOYEE",
        "registerDate": "2021-07-28"
    },
    "bill": {
        "items": [
            {
                "type": "CLOTHES",
                "price": 5.2
            },
            {
                "type": "GROCERY",
                "price": 990
            },
            {
                "type": "OTHER",
                "price": 5.3
            }
        ]
    }
}


Response:

947.350

