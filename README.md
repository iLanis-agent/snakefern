# Snakefern 1.0 TEST

Native Android Hebi puzzle. Android8+ (min26), target35. Package com.gg007.snakefern.

## Rules
Tap editable cells to cycle empty,1,2,3,4,5,empty. Build exactly TWO snakes, each with one1(head),2,3,4,5(tail) connected in order by sides. Different snakes cannot share an edge; diagonal contact is allowed. A head looks straight away from its2 until a black cell or the grid edge; it must not see any part of the OTHER snake. Its own body may be in that direction. A black arrow clue gives the first snake digit seen in its direction before another black cell or the grid edge, skipping empty cells. Zero means no snake digit in that ray. Gold segment givens are fixed.12 unique4x4 boards, each with two black arrow clues and0-4supplemental fixed segment digits, each with a unique full solution. Empty cells may remain. Undo/reset/next/levels and saved snake palette/empty-dot settings.

## Download and status
https://mega.co.nz/#!hVlkQBoQ!gcu6iNaF7YdpOdCPibFPiatK--js9UqNC17pzHWLSZs
APK SHA256 391ec82dd60f7136faeff8d8d8e08ae5ba3d86128194accb98cfc0a9c89c9687; 20974bytes. Original signing certificate SHA256 1651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. Anonymous download bytes match.

Independent Java follow-chain reconstruction, explicit inter-snake separation and coordinate-range nearest-cell checks agree with production occupied-component BFS and stepped sight rays on every disjoint pair of ordered five-cell paths on each board (676 to3612 pairs), plus60000random digit states per board. Unique solution, fixed-given and black locks, bounds, solve, undo and replay pass. Actual archived generator regeneration and archived Java tests pass. Drawing-adapter navigation, settings persistence, privacy, taps, completion storage, next and level selection pass. Game/menu/privacy/settings/levels/solved drawing pixels inspected, not phone screenshots. Phone runtime, performance and external browser handoff QA are incomplete. Signed TEST only, not final and not Play published.

## Functional difference
Live803-entry registry,115 recovered partial README records and semantic review of all141 cards in the exact Compassfern cumulative stage found no Hebi match. Neon Snake is real-time food collection and survival, not a static nearest-digit sightline puzzle. Stepgrove places one1-to9sequence with king moves and covers all cells; Snakefern places two separate five-cell side-connected sequences, permits empty cells, prevents inter-snake contact and forward head sight, and interprets blocked nearest-segment rays. Ribbonmere joins fixed endpoints with paths covering every cell; Snakefern chooses heads and tails under numerical sight clues and does not cover all cells. Known Hebi genre, not a global invention. Partial corpus, not ALL-local. Rules verified from https://www.nikoli.co.jp/en/puzzles/hebi/ and https://www.cross-plus-a.com/html/cros7hebi.htm .

## Build
JDK17 and Android SDK platform35/build-tools35.0.0. Run python generate-levels.py to reproduce levels.json. Board.java embeds the same generated black cells, directions, clues, givens and solutions. javac -d /tmp/compass-test src/com/gg007/snakefern/Board.java BoardTest.java and java -cp /tmp/compass-test com.gg007.snakefern.BoardTest. bash build.sh builds an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to private original signing inputs. No credentials in source. Release build settings, signed TEST artifact, not a final store release.

## Privacy and branding
Snakefern runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Snake palette, empty dots and completed-puzzle marks stay in the app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 icon copied byte-for-byte from preserved original. Menu includes studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation
Complete source and APK are privately preserved with exact cumulative staged HTML. GitHub https://github.com/iLanis-agent/snakefern holds README only; full Git source commit remains pending. Cumulative stage is NOT LIVE; existing studio run remains queued. No Pages setting changes, rollback or Play rollout. Updated November7,2026.
