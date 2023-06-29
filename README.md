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

![project-taskbuddy-1](https://github.com/luc-silva/Taskbuddy/assets/100732316/f0cfc65c-3705-468f-a0c7-0242e46f1688)
![project-taskbuddy-2](https://github.com/luc-silva/Taskbuddy/assets/100732316/754b78ab-bd18-41ce-9bf7-abe54aa487a3)
![project-taskbuddy-6](https://github.com/luc-silva/Taskbuddy/assets/100732316/d3b0712e-96c1-4fd0-9804-b61ca79b78fb)
![project-taskbuddy-5](https://github.com/luc-silva/Taskbuddy/assets/100732316/861b5ed8-1926-4b7f-bca3-5943aca5831f)


## Plans

- [ ] Add JWT
- [ ] Add BCrypt
