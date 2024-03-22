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










