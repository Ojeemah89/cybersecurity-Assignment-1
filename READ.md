# Network Security Tools Lab – Firewall Configuration

## Objective
The objective of this lab is to configure a basic firewall rule and test its effectiveness in controlling network traffic.

## Tool Used
- Windows Defender Firewall

## Configuration

### Inbound Rule:
- Blocked TCP traffic on Port 80 (HTTP)

### Outbound Rules:
- Blocked TCP traffic on Port 80 (HTTP)
- Blocked TCP traffic on Port 443 (HTTPS)

## Testing

### Before Configuration:
- Websites were accessible.

### After Configuration:
- Internet access was blocked
- Error: **ERR_NETWORK_ACCESS_DENIED**

## Result
The firewall successfully blocked HTTP and HTTPS traffic, preventing access to websites.

## Screenshots

### Inbound Rule (Port 80)
![Inbound](screenshots/inbound-rule-port80.png)

### Outbound Rule (Port 443)
![Outbound](screenshots/outbound-rule-port443.png)

### Test Result (Blocked Access)
![Blocked](screenshots/blocked-test-error.png)

## Conclusion
Firewalls are essential for controlling network traffic and protecting systems from unauthorized access.
