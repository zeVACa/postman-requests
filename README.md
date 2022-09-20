# postman-requests

post request https://blog.kata.academy/api/users

body: {
  "user": {
    "username": "logunik",
    "email": "logunik@bk.ru",
    "password": "555dan555"
  }
}

repsonse: {
    "user": {
        "username": "logunik",
        "email": "logunik@bk.ru",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzMmEyMDlhM2NmNzA1MWIwMDgyYTViMSIsInVzZXJuYW1lIjoibG9ndW5payIsImV4cCI6MTY2ODg4OTI0MiwiaWF0IjoxNjYzNzA1MjQyfQ.ryDVrshtvVxoCPbcKXBxfufRH6Tvm1ntdVAVSOMtgS0"
    }
}

------------------

https://blog.kata.academy/api/users/login

body: {
  "user": {
    "email": "logunik@bk.ru",
    "password": "555dan555"
  }
}

response: {
    "user": {
        "username": "logunik",
        "email": "logunik@bk.ru",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzMmEyMDlhM2NmNzA1MWIwMDgyYTViMSIsInVzZXJuYW1lIjoibG9ndW5payIsImV4cCI6MTY2ODg5Mjk1MywiaWF0IjoxNjYzNzA4OTUzfQ.VQeL-1cz0FPaGM67Tm0onOo1Bh9Z5MzA0pb5SHJ_z74"
    }
}

----------------------

https://blog.kata.academy/api/user

В Headers добавил Authorization Token eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzMmEyMDlhM2NmNzA1MWIwMDgyYTViMSIsInVzZXJuYW1lIjoibG9ndW5payIsImV4cCI6MTY2ODg5Mjk1MywiaWF0IjoxNjYzNzA4OTUzfQ.VQeL-1cz0FPaGM67Tm0onOo1Bh9Z5MzA0pb5SHJ_z74

response: {
    "user": {
        "username": "logunik",
        "email": "logunik@bk.ru",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzMmEyMDlhM2NmNzA1MWIwMDgyYTViMSIsInVzZXJuYW1lIjoibG9ndW5payIsImV4cCI6MTY2ODg5Mjk3MiwiaWF0IjoxNjYzNzA4OTcyfQ.wWB7bNgWWbw9RDhLDI1OVEzW5zNnnpQu2lPWlfQ6w6M"
    }
}
