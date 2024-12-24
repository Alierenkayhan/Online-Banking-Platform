# Base image
FROM node:latest

# Çalışma dizinini ayarla
WORKDIR /app

# package.json dosyasını kopyala
COPY package*.json ./

# Bağımlılıkları yükle
RUN npm install

# Tüm dosyaları kopyala
COPY . .

# Uygulamanın dinlediği portu belirt
EXPOSE 3000

# Geliştirme modunda başlat
CMD [ "npm", "run", "dev" ]
