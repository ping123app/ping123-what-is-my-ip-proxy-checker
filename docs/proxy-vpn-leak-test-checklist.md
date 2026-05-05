# Proxy and VPN Leak Test Checklist

This checklist helps you review a proxy or VPN setup before using it for browsing, QA, research, or account-environment testing.

Start with Ping123:

https://ping123.app/?utm_source=github&utm_medium=docs&utm_campaign=proxy_vpn_leak_test_checklist

## 1. Confirm the Public IP

Open Ping123 and record the visible public IP address.

Check:

- Did the IP address change after enabling the proxy or VPN?
- Does the country or region match the route you selected?
- Does the ASN, ISP, or organization match your provider expectation?
- Does the result stay stable after refreshing the page?

If the public IP did not change, the proxy or VPN may not be active for your browser.

## 2. Review Proxy and VPN Signals

Use the proxy checker workflow:

https://ping123.app/proxy-check/?utm_source=github&utm_medium=docs&utm_campaign=proxy_vpn_leak_test_checklist

Check:

- Is the IP flagged as proxy or VPN?
- Does the IP look like datacenter, hosting, residential, or mobile infrastructure?
- Is the ASN consistent with the type of network you expected?
- Is there any suspicious or high-risk reputation signal?

Not every proxy or VPN flag is bad. The important question is whether the classification matches your use case.

## 3. Run a DNS Leak Test

Use the DNS leak test:

https://ping123.app/dns-leak-test/?utm_source=github&utm_medium=docs&utm_campaign=proxy_vpn_leak_test_checklist

Check:

- Do DNS results match the same country or provider expectation?
- Do DNS resolvers reveal your original ISP?
- Do DNS results change after switching VPN exits?
- Are multiple resolvers appearing unexpectedly?

DNS behavior should make sense next to the visible public IP address.

## 4. Run a WebRTC Leak Test

Use the WebRTC leak test:

https://ping123.app/webrtc-leak-test/?utm_source=github&utm_medium=docs&utm_campaign=proxy_vpn_leak_test_checklist

Check:

- Does WebRTC expose an unexpected local or public network signal?
- Does the browser reveal a different network path from the main IP?
- Did browser extensions or privacy settings change the result?
- Is the result different in another browser profile?

WebRTC behavior can change after browser updates, extension updates, or VPN client changes.

## 5. Check Browser Coherence

Compare browser signals with the visible network profile.

Check:

- Browser language
- User agent
- Operating system hints
- Time zone
- Local time
- IP country and city
- DNS and WebRTC behavior

The setup is easier to reason about when these signals point to a consistent environment.

## 6. Re-Test After Every Change

Re-run the checks after changing:

- VPN exit location
- Proxy endpoint
- Browser profile
- Browser extensions
- Operating system network settings
- DNS settings
- WebRTC settings
- Device, router, or network

Small changes can alter the final browser and network profile.

## Quick Decision Guide

| Result | What it may mean | Next step |
|---|---|---|
| IP did not change | Proxy or VPN is not active for the browser | Recheck proxy/VPN routing |
| DNS shows original ISP | Possible DNS leak | Check VPN DNS settings |
| WebRTC shows unexpected path | Possible browser-side leak | Review WebRTC settings |
| IP is high risk | Reputation or network classification issue | Check IP risk details |
| Time zone mismatches IP region | Browser environment mismatch | Align time zone with route |

## Related Ping123 Tools

- What is my IP: https://ping123.app/?utm_source=github&utm_medium=docs&utm_campaign=proxy_vpn_leak_test_checklist
- Proxy checker: https://ping123.app/proxy-check/?utm_source=github&utm_medium=docs&utm_campaign=proxy_vpn_leak_test_checklist
- VPN leak test: https://ping123.app/vpn-leak-test-checklist/?utm_source=github&utm_medium=docs&utm_campaign=proxy_vpn_leak_test_checklist
- DNS leak test: https://ping123.app/dns-leak-test/?utm_source=github&utm_medium=docs&utm_campaign=proxy_vpn_leak_test_checklist
- WebRTC leak test: https://ping123.app/webrtc-leak-test/?utm_source=github&utm_medium=docs&utm_campaign=proxy_vpn_leak_test_checklist
