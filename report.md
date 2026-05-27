# Local iOS Pro Proof

Status: pass

Recorded after the app showed gateway connected. This is local Mantis-style evidence only; no GitHub workflow or Mantis system changes were made.

## Covered

- Gateway connected before recording: Settings showed Connection, Connected, address 127.0.0.1:18789, Agents 5.
- Tabs shown: Settings, Command, Agents, Chat.
- Fresh session: sent /new, then empty chat state appeared.
- Chat proof: sent hello and received visible assistant reply, "Hey Colin! What's up?"
- Voice proof: Start realtime chat changed to Stop realtime chat; gateway logs show talk.session.create, session.ready, appendAudio, and session.closed.

## Files

- ios-pro-proof.mp4: full simulator recording.
- ios-pro-proof-share.mp4: compressed sharing copy.
- ios-pro-proof.gif: lightweight GIF preview.
- ios-pro-proof-start.png: connected start frame.
- clean-proof-log.txt: trimmed gateway proof logs.
- mantis-evidence.json: local evidence manifest.

## Notes

Gateway status still reports CLI 2026.5.27 with running Gateway 2026.5.26. The app connected successfully and gateway logs show chat/talk traffic during proof.
