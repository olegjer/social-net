# social-net

## Запуск программы
### 1. Скачайте файлы на компьютер

### 2. Установите зависимости
Пройдите в папки server и client. В терминале напишите 
```bash
npm install
```

### 3. В папке server создайте файл .env и пропишите 
```javascript 
MONGO_URL='ВАШ URL В MONGODB'
JWT_SECRET='JWT_SECRET08789hj9r7ychijdhfd7237yr7fdudfj9uahfd2r8fu238fh3e09iejncau90uie'
PORT=3001
```

### 4. Загрузка данных в MongoDB
В папке server в файле index.js раскоментируйте 
```javascript 
// User.insertMany(users);
// Post.insertMany(posts);
```
после в теминале напишите 
```bash
npm start
```
закоментируйте обратно

### 5. Запуск
Пройдите в папки server и client. В терминале напишите
```bash
npm start
```



