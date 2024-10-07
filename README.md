# TrackWeatherMap

TrackWeatherMap is an application for monitoring weather conditions and planning routes based on weather changes. 
It is designed for travelers and technical services, such as emergency services, which need to quickly respond to weather changes.

# Main Features:
* View weather anywhere in the world
* Plan routes considering weather conditions
* User registration and authentication
* Administration: view and manage users, manage transport requests

# Technologies Used:
.Net 8, C#, ASP Net, JavaScript, API, MS SQL, Swagger, Unit tests, Docker

## Use Cases:
- **For travelers:** find places with good weather to plan trips.
- **For utility services:** monitor areas with adverse weather to dispatch special vehicles.

### Authentication Technology:
- User authentication is handled using Web Tokens (JWT).
- JWT is stored in cookies, thus maintaining the user session.

# Steps to launch the project:
Run the following command in the package manager console to update the database:
```
update-database
```
Add developer keys for YandexApi and OpenWeatherApi in the appsettings.json file.

![image](https://github.com/user-attachments/assets/b4e9c736-ce4b-4ab8-9194-008861fa3ca7)

**Docker Build**
Build the Docker image by running:
```
docker build -t trackweather/localtrackweather:v1 .
```
Then uncomment the database connection string for Docker.

![image](https://github.com/user-attachments/assets/0fb95e4b-d5d0-4cfc-9113-1d34443167bd)

Create and run the container:
```
docker-compose up --build
```
 
## Interface images 
### **Home page**

![Screenshot 2024-10-07 141454](https://github.com/user-attachments/assets/e356d136-24e5-4830-b8a3-90a4dff81273)

### **Weather route map**

![Screenshot 2024-10-07 142313](https://github.com/user-attachments/assets/b81f4293-2369-479b-9793-52648a922441)

### **Utility Service map**

![Screenshot 2024-10-07 141909](https://github.com/user-attachments/assets/46069a0b-b80b-4c38-bb1d-0569ab4ee9e2)

### **Vehicle Request List with Coordinates and Deletion**

![Screenshot 2024-10-07 141622](https://github.com/user-attachments/assets/8d369546-d3df-49f2-bdb9-12434bc700b5)

### **User List with Deletion**

![Screenshot 2024-10-07 141705](https://github.com/user-attachments/assets/0097de7a-0a40-4b36-862f-23207729bbe0)

### **User Addition page**

![Screenshot 2024-10-07 141717](https://github.com/user-attachments/assets/f856ad0b-c354-4b6d-a7f4-e37ead31c100)

### **Login page**

![Screenshot 2024-10-07 141557](https://github.com/user-attachments/assets/9f596b97-a2a2-4048-9829-798c28aad1eb)

### User Profile
**Logged In**            |  **Not Logged In**
:-------------------------:|:-------------------------:
![Screenshot 2024-10-07 142324](https://github.com/user-attachments/assets/5b61b23e-c0c0-4f66-924d-5cf65c50d5be)  |  ![Screenshot 2024-10-07 142335](https://github.com/user-attachments/assets/0a87bcf3-c6d4-412e-989d-da52b35707d8)

### **Swagger window**

![image](https://github.com/user-attachments/assets/94ac7b50-6f50-455d-a86c-7b5e45d5c5db)

