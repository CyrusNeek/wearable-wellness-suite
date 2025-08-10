# Wearable Wellness Suite (Airline + Hospital)

This repo includes a runnable **mobile app scaffold (Expo/React Native)** and **starter watch shells** for Wear OS and Tizen, aligned with your spec.

## Projects
- `/mobile-expo` – React Native (Expo) with screens: Dashboard, Calendar, Planner, Privacy. Mock wearable data + simple on-device risk logic.
- `/wearos-stub` – Kotlin/Compose starter showing quick actions (skeleton, copy into Android Studio).
- `/tizen-stub` – Web app skeleton for Tizen (HTML/JS).

## Run Mobile (Mock Mode)
```bash
cd mobile-expo
npm install
npm run dev
# Scan QR with Expo Go on iOS/Android or run emulator
```

## Extend
- Replace `/mobile-expo/src/logic/mock.ts` with real wearable SDK reads.
- Port `useRisk` to a TensorFlow Lite model.
- Add schedule connectors via your preferred APIs.
- Keep all health data on-device. Share only anonymized counters if needed.

MIT License
