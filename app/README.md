
# Beer Rating App (v1.1.1 — corrected)

- **Mobile app:** Expo React Native
- **API:** Express + SQLite
- Weighted metrics + Bayesian public score
- Map of nearby venues with their best pint
- Film-inspired color palette applied (colors only)

## Run the API
```bash
cd server
npm install
npm run seed
npm run dev
# http://localhost:3001
```

## Run the app
```bash
cd app
npm install
npm start
# If asked: npx expo install react-native-maps expo-location
```

If using a physical device, set `src/config.ts` → `API_URL` to your machine's LAN IP.
