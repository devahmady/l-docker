# Gunakan image dari docker community yang sudah ada, disini menggunakan alpine-linux yang sudah terinstal node versi 16.17
# Jalankan perintah untuk update package list
FROM node:16.17-alpine


# Deskripsikan direktori project di dalam container docker nanti
# Copy semua file project ke dalam direktori /app
WORKDIR /usr/src/l-docker
# Jalankan perintah untuk install & build next.js
COPY ./frontend/ /usr/src/l-docker/
# RUN npm install
# RUN npm run build

# Definikan port yang akan digunakan dalam container docker

# Jalankan npm run start di terminal
ENTRYPOINT npm start
