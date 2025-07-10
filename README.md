# ═══════════════════════════════════════════════════════════════
# VARIABLES GLOBALES PARTAGÉES
# ═══════════════════════════════════════════════════════════════
NODE_ENV=development
FRONTEND_URL=http://localhost:3000
CLIENT_URL=http://localhost:3000
CORS_ORIGIN=http://localhost:3000

# JWT CONFIGURATION (OBLIGATOIRE - partagé par tous les services)
JWT_SECRET=roadTripTopSecret2024-super-secure-key
JWT_REFRESH_SECRET=roadTripRefreshSecret2024-ultra-secure
JWT_EXPIRES_IN=24h
JWT_REFRESH_EXPIRES_IN=7d

# DATABASE CONFIGURATION (OBLIGATOIRE)
MONGODB_URI=mongodb://localhost:27017/roadtrip-dev
MONGO_URI=mongodb://localhost:27017/roadtrip-dev

# ═══════════════════════════════════════════════════════════════
# NOTIFICATION SERVICE (Port 5005)
# ═══════════════════════════════════════════════════════════════
# Variables spécifiques à notification-service

# Port et config
PORT=5005
SERVICE_NAME=notification-service
API_KEY=your-notification-api-key-here

# Email (Mailjet)
MAILJET_API_KEY=your-mailjet-api-key-here
MAILJET_API_SECRET=your-mailjet-secret-key-here
EMAIL_FROM_NAME=ROADTRIP
EMAIL_FROM_ADDRESS=noreply@roadtrip.fr

# SMS (Free Mobile)
FREE_MOBILE_USERNAME=your-free-mobile-username
FREE_MOBILE_API_KEY=your-free-mobile-api-key

# Firebase (optionnel pour push notifications)
FIREBASE_PROJECT_ID=your-firebase-project-id
FIREBASE_CLIENT_EMAIL=your-firebase-client-email
FIREBASE_PRIVATE_KEY=your-firebase-private-key
SMS_API_KEY=your-sms-api-key

# URLs
DATA_SERVICE_URL=http://localhost:5002
DATA_SERVICE_URL_DOCKER=http://data-service:5002
