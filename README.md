# Azure-Security-and-Monitoring

### Containerize the application 

### Backend

```
git clone https://github.com/UnpredictablePrashant/ResumeAI backend
```

Create a .env file with the following fields
```
JWT_SECRET_KEY="MYREALLYSECRETKEY"
MONGO_URL="mongodb://MONGO_URL"
OPENAI_KEY="OPENAI_API_KEY"
GMAIL_USER="THIS EMAIL IS USED TO SEND RESUMES"
GMAIL_PASS="PASSWORD USED BY NODEMAILER"
FRONT_END="URL FOR FRONTEND"
```

Run the below command to containerize the application backend.

```
docker build -t backend .
```
![image](https://github.com/AdarshIITDH/Azure-Security-and-Monitoring/assets/60352729/64961305-f776-44ff-931f-07cf46d055ea)
![image](https://github.com/AdarshIITDH/Azure-Security-and-Monitoring/assets/60352729/b3325426-58a2-44c6-a03f-f13644fcce50)

backend container 

![image](https://github.com/AdarshIITDH/Azure-Security-and-Monitoring/assets/60352729/aac10b78-03fb-4fae-9acc-8f32f8894ea2)


### Frontend

```
git clone https://github.com/UnpredictablePrashant/ResumeAI frontend
```

Run the below command to containerize the application backend.

```
docker build -t frontend .
```



frontend container 







### Azure Dashboard

Home > Dashboard

![image](https://github.com/AdarshIITDH/Azure-Security-and-Monitoring/assets/60352729/a3660c3d-5d4f-425b-946e-bcb67b3d38c7)

Add a tile in the dashboard that will be Metric Chart

![image](https://github.com/AdarshIITDH/Azure-Security-and-Monitoring/assets/60352729/8b39a879-3df1-424f-97f9-c1913ad5ea9c)

Edit the mertic

![image](https://github.com/AdarshIITDH/Azure-Security-and-Monitoring/assets/60352729/282891f4-ded3-445e-a985-3f4a79069b82)


![image](https://github.com/AdarshIITDH/Azure-Security-and-Monitoring/assets/60352729/e5866a90-b089-4ced-8169-9c49f803bce2)

In same manner add other tiles like memory utilisation and disk utilisation

![image](https://github.com/AdarshIITDH/Azure-Security-and-Monitoring/assets/60352729/d914ea5c-263f-4f4d-9e37-c8f46be89c71)



### Backend Dashboard
![image](https://github.com/AdarshIITDH/Azure-Security-and-Monitoring/assets/60352729/c68df075-fe45-4492-bcf9-727ada13027e)



## Full Dashboard

![image](https://github.com/AdarshIITDH/Azure-Security-and-Monitoring/assets/60352729/a27a265c-1545-4f4a-b5ab-d1b6aa4f31ff)

