# Taskbuddy-API

To-do manager made by me with Typescript and React as a project for The Odin Project curriculum.

## Usage

### Method 1 (requires docker compose)

1 - Download the repository into your machine:
```git clone https://github.com/luc-silva/taskbuddy --recursive```

2 - Go to folder:
```cd taskbuddy```

3 - Run docker compose, may take a while to load:
```sudo docker compose up -d```

4 - Open Taskbuddy web page.
    - localhost:3000/

### Method 2 (requires Node, JDK-11, Maven and MySql)

1 - Download the repository into your machine:
```git clone https://github.com/luc-silva/taskbuddy --recursive```

2 - Go to folder:
```cd taskbuddy```

3 - Install client dependencies:
```cd Taskbuddy-client; npm install```

4 - Start Client Server:
```npm start```

5 - Start API Server:
```cd ..; cd Taskbuddy-api; mvn spring-boot:run```

## Images

![todo1](https://user-images.githubusercontent.com/100732316/219161697-d570ba52-66e6-4a8d-8384-6495e9e5387c.png)
![todo2](https://user-images.githubusercontent.com/100732316/219161715-353ac968-96b8-4657-850e-ff57dbe54ba6.png)
![todo3](https://user-images.githubusercontent.com/100732316/219161719-ad157bde-e120-47b9-946b-c43e9359ae02.png)
![todo4](https://user-images.githubusercontent.com/100732316/219161725-3329e7da-cdbe-4b95-b70b-259917b4bed6.png)
