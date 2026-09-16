# Play over the internet

Myrtana Accord uses UDP port `33123`.

## Tailscale

This is the easiest option.

1. Every player installs [Tailscale](https://tailscale.com/download) and signs in.
2. The host gives friends access to their Tailscale network. All PCs must be
   connected to that network.
3. The host starts a campaign in the Myrtana Accord launcher.
4. Friends enter the host's `100.x.y.z` address or join code.

The installer can install Tailscale for you.

## Local network or another VPN

If all PCs are on the same home network, use the host's local address. For a
different virtual network, every player can install
[ZeroTier](https://www.zerotier.com/download/) and join the same network. Enter
the host's local or VPN address in the launcher.

## Port forwarding

The host can forward UDP port `33123` to their PC. Use a session password when
the server is open to the internet.

## Connection problems

- Check that the host server is running.
- Check the host address.
- Check that every player is connected to the same VPN.
- Allow Myrtana Accord through Windows Firewall.
- Make sure every player uses the same mod version.

For help, contact **Yevh** at **yevhsec1@gmail.com**.
