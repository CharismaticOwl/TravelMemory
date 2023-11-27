# Travel Memory

`.env` file to work with the backend:

```
MONGO_URI='ENTER_YOUR_URL'
PORT=3000
```

Data format to be added: 

```json
{
    "tripName": "Incredible India",
    "startDateOfJourney": "19-03-2022",
    "endDateOfJourney": "27-03-2022",
    "nameOfHotels":"Hotel Namaste, Backpackers Club",
    "placesVisited":"Delhi, Kolkata, Chennai, Mumbai",
    "totalCost": 800000,
    "tripType": "leisure",
    "experience": "Lorem Ipsum, Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum,Lorem Ipsum, ",
    "image": "https://t3.ftcdn.net/jpg/03/04/85/26/360_F_304852693_nSOn9KvUgafgvZ6wM0CNaULYUa7xXBkA.jpg",
    "shortDescription":"India is a wonderful country with rich culture and good people.",
    "featured": true
}
```
Solution:

Create an account and deploy a cluster on MongoDB
Once deployed create a login credentials of read and write permission
Use MongoDBCompass to test the login URL

Create two Ec2 instance - preferred Ubuntu - named - Satya_TM_FE, and Satya_TM_BE

Update and Upgrade OS
```
sudo apt update && sudo apt upgrade -y
```

install git on  both the instances

```shell
sudo apt-get install git -y
```

clone the git repo

```
git clone https://github.com/CharismaticOwl/TravelMemory.git
```
Install nodejs and npm on both the instances
```

```

Steps divided in two parts part A for backend and part B for frontend

PART - A, Deplo backend

