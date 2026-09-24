# Domino

Domino is a mobile social challenge app built around private groups completing a shared daily challenge.

Group members join using invite codes, complete the daily DOMINO within a time limit, and submit photo, video or text proof. The app also includes notifications, challenge history, and group-based access controls.

> Production source code is maintained in a private repository.

## Tech Stack

- React Native
- Expo
- TypeScript
- Supabase
- PostgreSQL
- Authentication
- Storage
- Edge Functions
- Push Notifications
- Git / GitHub

## Core Features

- Private challenge groups
- Invite-code joining
- Daily challenge generation
- Configurable challenge time limits
- Photo, video and text proof
- Push notifications
- Group history
- Membership-based access controls
- Shared group state
- Mobile media workflows

## Engineering Highlights

- Built a React Native and Expo application using TypeScript.
- Integrated Supabase authentication, database and storage services.
- Implemented group creation and invite-code joining workflows.
- Added support for daily challenges with configurable time limits.
- Built media-proof flows for photos and videos.
- Implemented push notification workflows through backend functions.
- Added protected historical reveal logic so past challenge content is available only to valid group members.
- Improved shared application state so group settings persist correctly across navigation.
- Debugged duplicate group creation and improved mutation behavior to reduce repeated writes.
- Built loading, joined, empty and error states across group flows.

## Backend & Shared State

Important shared application rules are handled through backend data and functions rather than relying only on client-side logic.

This includes:

- Group membership
- Historical challenge access
- Notification workflows
- Shared challenge state
- Media access

## Development Focus

Domino was developed with an emphasis on multi-user behavior and reliable group state.

Development included:

1. Authentication
2. Group creation
3. Invite-code joining
4. Daily challenges
5. Timed completion flows
6. Photo/video/text proof
7. Push notifications
8. Historical access controls
9. Shared-state debugging
10. UI and navigation refinement

## Source Code

The main application repository is private.

This public repository documents the architecture, technologies and engineering work completed on Domino.

## Developer

**Risto Caissie**  
Software Developer — Calgary, Alberta

📧 ristocaissie1@gmail.com
