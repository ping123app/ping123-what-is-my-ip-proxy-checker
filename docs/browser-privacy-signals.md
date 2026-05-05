# Browser Privacy Signals

Your public IP address is only one part of your online profile. Websites may also see browser-level signals such as user agent, language, time zone, WebRTC behavior, DNS behavior, and device hints.

Ping123 helps you inspect these signals together:

https://ping123.app/?utm_source=github&utm_medium=docs&utm_campaign=browser_privacy_signals

## Public IP vs Browser Signals

A basic IP checker answers one question: what public IP address can a website see?

A privacy diagnostic tool asks a broader question: does the whole browser and network environment make sense together?

Useful signals include:

- Public IP address
- IP country and city
- ASN, ISP, and organization
- Proxy and VPN indicators
- DNS resolver behavior
- WebRTC network exposure
- User agent
- Operating system hints
- Browser language
- Time zone
- Local time

## Why Coherence Matters

Browser and network signals can become inconsistent. For example:

- The public IP is in one country, but the browser time zone points to another.
- DNS behavior reveals a resolver outside the expected route.
- WebRTC exposes a network path that does not match the visible IP.
- Browser language does not match the region you are testing.
- A proxy route changes the IP, but the rest of the browser profile remains unchanged.

These mismatches are useful debugging clues.

## Browser Privacy Review Steps

1. Open Ping123 and record the public IP.
2. Check IP country, city, ASN, ISP, and organization.
3. Run the DNS leak test.
4. Run the WebRTC leak test.
5. Compare browser language and time zone against the visible IP region.
6. Save a baseline result for a known-good browser profile.
7. Re-test after updates or configuration changes.

## What to Check After Browser Updates

Browser updates can change privacy behavior. Re-test after:

- Browser version updates
- Extension updates
- VPN client updates
- Proxy profile changes
- DNS setting changes
- Operating system updates
- Moving between desktop, mobile, Wi-Fi, and mobile data

## Related Ping123 Tools

- What is my IP: https://ping123.app/?utm_source=github&utm_medium=docs&utm_campaign=browser_privacy_signals
- DNS leak test: https://ping123.app/dns-leak-test/?utm_source=github&utm_medium=docs&utm_campaign=browser_privacy_signals
- WebRTC leak test: https://ping123.app/webrtc-leak-test/?utm_source=github&utm_medium=docs&utm_campaign=browser_privacy_signals
- VPN leak test: https://ping123.app/vpn-leak-test-checklist/?utm_source=github&utm_medium=docs&utm_campaign=browser_privacy_signals
