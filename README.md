
# Adwa Fight Night App

> Premium Pay-Per-View streaming platform for Adwa Fight Night 2026.

## Overview

Adwa Fight Night is a Flutter application delivering a secure PPV experience for combat sports fans. Users register with their phone number, purchase access through Chapa, and watch the live event via Cloudflare Stream. Historical fights, fighter profiles, and community links keep fans engaged before and after the event.

## Goals

- Frictionless PPV purchase flow
- Secure HD live streaming
- Premium cinematic UI
- Reliable payment verification
- Scalable architecture

## Core Features

- Authentication (Phone + Name)
- Firebase Authentication
- Firestore user profiles
- Chapa payments
- Cloudflare Stream player
- Countdown to event
- YouTube classic fights
- Profile & PPV status
- Push notifications
- Admin dashboard

## Technology Stack

| Layer | Technology |
|--------|------------|
| Frontend | Flutter |
| State | Riverpod |
| Backend | Firebase |
| Database | Firestore |
| Authentication | Firebase Auth |
| Streaming | Cloudflare Stream |
| Payments | Chapa API |
| Analytics | Firebase Analytics |
| Notifications | Firebase Messaging |

## Project Structure

```text
lib/
  core/
  shared/
  features/
      auth/
      home/
      payment/
      livestream/
      profile/
      videos/
```

## Development Roadmap

### Phase 1
- Flutter setup
- Theme
- Authentication
- Firestore
- Shared Preferences

### Phase 2
- Home Dashboard
- Countdown
- Locked Hero

### Phase 3
- Chapa Integration

### Phase 4
- Cloudflare Live Streaming

### Phase 5
- YouTube Archive

### Phase 6
- Profile
- Notifications

### Phase 7
- Admin Dashboard

### Phase 8
- Production Release

## Environment Variables

```
CHAPA_PUBLIC_KEY=
FIREBASE_PROJECT_ID=
CLOUDFLARE_STREAM_URL=
```

## Security

- Server-side payment verification
- Signed streaming URLs
- Firebase Security Rules
- HTTPS only

## UI Theme

- Background: #0A0A0A
- Surface: #1A1A1A
- Accent: #FF1E27

## CI/CD

- GitHub Actions
- Flutter Analyze
- Flutter Test
- Android Build
- iOS Build

## License

Private © Sweatbox APG
