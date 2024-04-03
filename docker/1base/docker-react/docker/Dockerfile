FROM node:14-alpine

# Thiết lập thư mục làm việc mặc định trong container
WORKDIR /app

# Sao chép các file package.json và package-lock.json vào thư mục làm việc
COPY ../package*.json ./

# Cài đặt dependencies
RUN npm install

# Sao chép tất cả các file trong dự án vào thư mục làm việc
COPY .. .

# Build ứng dụng React
RUN npm build

# Port mà ứng dụng React chạy trên container
EXPOSE 3000

# Command để chạy ứng dụng React
CMD ["npm", "start"]