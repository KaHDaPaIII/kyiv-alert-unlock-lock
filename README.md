# Kyiv Alert -> Unlock Lock

Monitors Kyiv’s air alerts via the [alerts.com.ua](https://alerts.com.ua) API every minute using **GitHub Actions**.  
Sends a cURL request to defined URL (e.g. webhook to unlock lock) in GitHub Secrets during active alert in Kyiv.
