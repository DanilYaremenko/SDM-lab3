## Console application with chalk library

This console application shows the most popular words of Ronnie Coleman and his name ASCII format.

### How to run:
1. At first, you need nodejs installed on your local machine.

2. Clone repository:
```bash
git clone https://github.com/DanilYaremenko/SDM-lab3.git
```
3. Follow the folder:
```bash
cd SDM-lab3/starter-project-nodejs
```
4. Install dependecies:
```bash
npm install
```
5. Run the program:
```bash
npm start
```
or
```bash
node main.mjs
```

### How to run using Docker:

1. At first, you need Docker to be installed on your local machine.

2. Clone repository:
```bash
git clone https://github.com/DanilYaremenko/SDM-lab3.git
```
3. Follow the folder:
```bash
cd SDM-lab3/starter-project-nodejs
```
4. Build the image:
```bash
docker build . -t yeah-buddy
```
5. Run the container:
```bash
docker run --tty yeah-buddy
```