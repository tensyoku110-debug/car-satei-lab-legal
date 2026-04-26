# Privacy Policy - 車査定ラボ Auto Posting Tool

**Last updated**: 2026-04-27

## 1. Information We Access via TikTok API

This application accesses the following from TikTok:
- **TikTok account ID and basic profile** (via `user.info.basic` scope)
- **Permission to upload videos** (via `video.upload` scope)
- **Permission to publish videos** (via `video.publish` scope, after approval)

## 2. Information We Do NOT Collect

The App does NOT collect or process any of the following:
- Viewer demographics, comments, watch time, follower lists
- Direct messages, hashtag analytics, or trend data
- Any TikTok user data other than the brand-owned account
- Personal information of viewers or other TikTok users
- Cookies or tracking pixels of any kind

## 3. Data Storage

- **OAuth access/refresh tokens**: Stored locally on a single Mac in
  `config/tiktok_token.json`. Never transmitted to any third-party server
  except TikTok's official API endpoints.
- **Generated videos and captions**: Stored locally on the brand owner's Mac
  before being uploaded directly to TikTok via the official API.
- **No cloud sync**: No automatic upload of OAuth tokens or content metadata
  to any external service.

## 4. Data Transmission

- All API communication is over HTTPS to `open.tiktokapis.com` and `tiktok.com`
- No data is sent to any other domain or third-party service

## 5. Third-Party Services

The App uses the following services:
- **TikTok Content Posting API** — for video upload and publication
- **ngrok** (only during initial OAuth) — for OAuth callback redirect

The App does NOT use any analytics, advertising networks, or telemetry services.

## 6. Data Retention

- OAuth tokens are retained until manually revoked by the user or until
  TikTok expires them
- Generated content remains on the local Mac per the user's file system policy

## 7. User Rights

The brand owner can:
- Revoke OAuth authorization at any time via TikTok's app management page
- Delete local tokens by removing `config/tiktok_token.json`
- Stop the App by disabling launchd schedules

## 8. Children's Privacy

The App is operated by an adult brand owner and posts content categorized as
"not made for kids". Content does not target children under 13.

## 9. Changes

This privacy policy may be updated. Latest version is always at the URL where
this document is hosted.

## 10. Contact

For privacy questions: tensyoku110@gmail.com
