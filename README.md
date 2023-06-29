# Taskbuddy-API

Taskbuddy is a to-do manager made by me initialy as a project for The Odin Project curriculum.
Client was made with Typescript & React while API with Java and Spring-boot.

## Usage

### Method 1 (requires docker compose)

1 - Download the repository into your machine:

```bash
git clone https://github.com/luc-silva/Taskbuddy --recursive
```

2 - Go to folder:

```bash
cd Taskbuddy
```

3 - Run docker compose, may take a while to load:

```bash
cd Taskbuddy; sudo docker compose up -d
```

4 - Open Taskbuddy web page (localhost:3000)

### Method 2 (requires Node, JDK-11, Maven and MySql)

#### Important

- Check if ports 3000 and 8080 are available.
- You can replace MySQL with H2 Database by setting the test profile at ```Taskbuddy-API/src/main/resources/application-test.properties```

1 - Download the repository into your machine:

```bash
git clone https://github.com/luc-silva/taskbuddy --recursive
```

2 - Go to folder:

```bash
cd taskbuddy
```

3 - Install client dependencies:

```bash
cd Taskbuddy-client; npm install
```

4 - Start Client Server:

```bash
npm start
```

5 - Start API Server:

```bash
cd ..; cd Taskbuddy-api; mvn spring-boot:run
```

## Images

![todo1](https://user-images.githubusercontent.com/100732316/219161697-d570ba52-66e6-4a8d-8384-6495e9e5387c.png)
![todo2](https://user-images.githubusercontent.com/100732316/219161715-353ac968-96b8-4657-850e-ff57dbe54ba6.png)
![todo3](https://user-images.githubusercontent.com/100732316/219161719-ad157bde-e120-47b9-946b-c43e9359ae02.png)
![todo4](https://user-images.githubusercontent.com/100732316/219161725-3329e7da-cdbe-4b95-b70b-259917b4bed6.png)

## Plans

- [ ] Add JWT
- [ ] Add BCrypt
