# Ping123 - What Is My IP, Proxy Checker, VPN Leak Test

Ping123 is a transparent IP checker and browser privacy diagnostic tool for checking your public IP address, proxy status, VPN signals, DNS leak behavior, WebRTC leak exposure, browser fingerprint basics, and IP risk context.

Start here:

https://ping123.app/?utm_source=github&utm_medium=repo&utm_campaign=what_is_my_ip_proxy_checker

## Quick Answer: What Is My IP?

Your public IP address is the network address websites can see when your browser connects to them. A basic "what is my IP" page only shows that address. Ping123 goes further by helping you review whether your IP, DNS, WebRTC, browser, and risk signals tell the same story.

Use Ping123 when you need to:

- Check your current public IP address
- Verify whether a proxy or VPN route is active
- Run a VPN leak test before using an account or dashboard
- Check for DNS leak and WebRTC leak exposure
- Review IP risk, IP reputation, and proxy or VPN indicators
- Compare your browser environment before and after network changes

## What Ping123 Checks

Ping123 is designed around practical privacy and network diagnostics:

- Public IP address
- IP location and network metadata
- ASN, ISP, and organization context
- Proxy checker signals
- VPN detection signals
- Datacenter, residential, and suspicious network hints
- DNS leak test workflow
- WebRTC leak test workflow
- Browser user agent and device context
- Browser language and time zone coherence
- IP risk score and IP reputation context

The goal is not just to show an IP address. The goal is to help you understand whether your full browser and network setup is coherent.

## Main Tools

| Tool | What it helps you verify | Link |
|---|---|---|
| What Is My IP | Your public IP and visible network profile | https://ping123.app/?utm_source=github&utm_medium=repo&utm_campaign=what_is_my_ip_proxy_checker |
| Proxy Checker | Whether your route looks like a proxy, VPN, datacenter, or normal network | https://ping123.app/proxy-check/?utm_source=github&utm_medium=repo&utm_campaign=proxy_checker |
| VPN Leak Test | Whether your VPN setup has visible mismatch or leak signals | https://ping123.app/vpn-leak-test-checklist/?utm_source=github&utm_medium=repo&utm_campaign=vpn_leak_test |
| DNS Leak Test | Whether DNS behavior may expose the wrong resolver path | https://ping123.app/dns-leak-test/?utm_source=github&utm_medium=repo&utm_campaign=dns_leak_test |
| WebRTC Leak Test | Whether browser WebRTC behavior exposes unexpected network signals | https://ping123.app/webrtc-leak-test/?utm_source=github&utm_medium=repo&utm_campaign=webrtc_leak_test |
| IP Risk Score | IP reputation, proxy, VPN, and abuse-risk context | https://ping123.app/ip-risk/?utm_source=github&utm_medium=repo&utm_campaign=ip_risk_score |

## Why This Matters

Many privacy checks fail because users only look at one signal. A VPN may change the visible IP address while DNS, WebRTC, browser language, time zone, or IP reputation still creates a mismatch.

Ping123 is useful because it brings these checks into one manual workflow:

1. Confirm the visible public IP address.
2. Compare the IP location, ASN, ISP, and organization.
3. Check proxy, VPN, datacenter, and risk indicators.
4. Run DNS and WebRTC leak checks.
5. Review browser context such as user agent, language, and time zone.
6. Re-test after changing browsers, VPN exits, proxies, networks, or privacy settings.

## Common Use Cases

### Check If a Proxy Is Working

Open Ping123 after connecting to a proxy. Confirm that the displayed IP, ASN, location, and proxy checker signals match what you expected. If the IP changed but DNS or WebRTC still looks inconsistent, your setup may need more review.

Proxy checker:

https://ping123.app/proxy-check/?utm_source=github&utm_medium=repo&utm_campaign=proxy_checker

### Run a VPN Leak Test

A VPN can hide your original public IP, but some environments may still expose inconsistent DNS, WebRTC, time zone, or browser signals. Ping123 helps you inspect these signals manually before you rely on a new VPN route.

VPN leak test:

https://ping123.app/vpn-leak-test-checklist/?utm_source=github&utm_medium=repo&utm_campaign=vpn_leak_test

### Run a DNS Leak Test

A DNS leak can happen when DNS requests are sent outside the expected VPN or proxy route. This can reveal resolver or network information that does not match your visible IP address.

DNS leak test:

https://ping123.app/dns-leak-test/?utm_source=github&utm_medium=repo&utm_campaign=dns_leak_test

### Run a WebRTC Leak Test

WebRTC can expose network-related information in some browser setups. Ping123 provides a simple WebRTC leak test workflow so you can compare browser-side signals against your visible public IP.

WebRTC leak test:

https://ping123.app/webrtc-leak-test/?utm_source=github&utm_medium=repo&utm_campaign=webrtc_leak_test

### Check IP Risk Before a Login or Test Session

Some IP addresses have reputation or abuse-risk signals because of datacenter use, proxy infrastructure, VPN ranges, spam history, or other network-level patterns. Ping123 helps you review these signals before using a sensitive environment.

IP risk score:

https://ping123.app/ip-risk/?utm_source=github&utm_medium=repo&utm_campaign=ip_risk_score

## Signal Checklist

Use this quick checklist when testing an IP, proxy, or VPN route:

- Does the public IP match the route you intended to use?
- Does the IP country, city, ASN, ISP, and organization make sense?
- Is the route marked as proxy, VPN, Tor, hosting, datacenter, or risky?
- Does DNS behavior match the same region or provider expectation?
- Does WebRTC expose unexpected local or public network information?
- Do browser language and time zone match the visible network profile?
- Did the result change after browser, extension, VPN, proxy, or OS updates?

For a longer version, see:

- [Proxy and VPN Leak Test Checklist](docs/proxy-vpn-leak-test-checklist.md)
- [IP Risk Signals Explained](docs/ip-risk-signals.md)
- [Browser Privacy Signals](docs/browser-privacy-signals.md)
- [FAQ](docs/faq.md)

## Ping123 vs Basic IP Checker Sites

| Feature | Basic IP checker | Ping123 |
|---|---:|---:|
| Shows public IP | Yes | Yes |
| IP location context | Sometimes | Yes |
| ASN and ISP context | Sometimes | Yes |
| Proxy checker workflow | Rarely | Yes |
| VPN leak test workflow | Rarely | Yes |
| DNS leak test workflow | Rarely | Yes |
| WebRTC leak test workflow | Rarely | Yes |
| IP risk context | Rarely | Yes |
| Browser privacy context | Rarely | Yes |
| Manual troubleshooting flow | No | Yes |

## Who Is Ping123 For?

Ping123 is useful for:

- Developers testing IP-based features
- QA engineers checking location-sensitive flows
- Network administrators debugging routing behavior
- Privacy-conscious users reviewing browser exposure
- Proxy and VPN users verifying connection consistency
- Security and trust teams reviewing IP reputation context
- Growth and operations teams testing network quality responsibly

## FAQ

### What is my IP address?

Your public IP address is the address websites see when your browser connects to them. It can identify your visible network route, approximate location, ISP, ASN, or organization.

### How do I check whether my proxy is working?

Connect to the proxy, open Ping123, and compare the visible IP, location, ASN, proxy signals, DNS behavior, and WebRTC behavior with what you expected.

### Can a VPN leak my real IP address?

Yes. A VPN setup can still reveal inconsistent DNS, WebRTC, browser, time zone, or routing signals. Ping123 helps you manually check those signals.

### What is a DNS leak?

A DNS leak happens when DNS requests are routed outside the expected VPN or proxy tunnel. This can expose resolver or network information that does not match your visible IP.

### What is a WebRTC leak?

A WebRTC leak happens when browser WebRTC behavior exposes unexpected network-related information. Testing WebRTC is especially useful after changing browsers, VPN tools, proxy settings, or extensions.

### What is an IP risk score?

An IP risk score is a summary of reputation and network indicators, such as proxy or VPN classification, datacenter signals, abuse history, spam patterns, or suspicious infrastructure.

## Related Resources

- IP risk score: https://ping123.app/ip-risk/?utm_source=github&utm_medium=repo&utm_campaign=ip_risk_score
- Proxy checker: https://ping123.app/proxy-check/?utm_source=github&utm_medium=repo&utm_campaign=proxy_checker
- DNS leak test: https://ping123.app/dns-leak-test/?utm_source=github&utm_medium=repo&utm_campaign=dns_leak_test
- WebRTC leak test: https://ping123.app/webrtc-leak-test/?utm_source=github&utm_medium=repo&utm_campaign=webrtc_leak_test
- VPN leak test: https://ping123.app/vpn-leak-test-checklist/?utm_source=github&utm_medium=repo&utm_campaign=vpn_leak_test

## Start Here

Check your IP address, proxy status, DNS leak behavior, WebRTC leak exposure, VPN consistency, browser privacy signals, and IP risk context:

https://ping123.app/?utm_source=github&utm_medium=repo&utm_campaign=what_is_my_ip_proxy_checker

## License

MIT
