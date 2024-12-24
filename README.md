# Online-Banking-Platform
From Youtube Tutorial => https://www.youtube.com/watch?v=DwbwuYYiBTk

Docker Hub repo => https://hub.docker.com/r/alieren/online_banking_platform

Docker file dan container build etme
docker build -t online_banking_platform_tutorial:latest .

Docker file'ı çalıştırma
docker run -p 3000:3000 online_banking_platform_tutorial:latest

Container'ı Durdurma
docker ps
docker stop <CONTAINER_ID>

Docker Hub a gönderme için
Docker Hub'da Giriş Yapma => docker login
Docker İmajı Etiketleyin => docker tag online_banking_platform_tutorial:latest alieren/online_banking_platform:1.0.0