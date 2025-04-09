FROM mcr.microsoft.com/playwright:v1.43.1-jammy

WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .

# Można tu też dodać domyślny skrypt do odpalenia, np. testowe logowanie:
CMD ["node", "scripts/login.js"]
