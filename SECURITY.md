# Security

Please report security problems privately, not in a public issue.

**How:** this repository's **Security** tab → **Report a vulnerability**. Only the maintainers see the report.

Include what you found, how to reproduce it, and the version (`emma --version`). You will get an answer within
a few days; fixes go out as a signed release that servers pick up by themselves.

## What emma does to stay safe

- Releases are signed (ed25519); the installer checks sha256, and updates check the signature before switching.
- Tokens are stored as hashes; web sign-ins are per-device HttpOnly cookies.
- Use HTTPS for anything beyond a quick try: over plain HTTP, tokens and messages cross the network unencrypted.

---

# 보안

보안 문제는 공개 이슈가 아니라 비공개로 알려 주세요: 이 저장소의 **Security** 탭 → **Report a vulnerability**.
무엇을 찾았는지, 재현 방법, 버전(`emma --version`)을 적어 주세요.
