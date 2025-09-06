#### Bot Protection Script

- This script helps protect your site from bots by detecting human-like interaction patterns. It can be embedded easily in any site.
- In index.html or root file of the project folder embed the following script tags mentioned below.
- Also insert your GTM-ID in the script.

```
<script>
        window.botProtectionConfig = { gtmId: "GTM-XXXXXXXX" };
</script>

<script src="https://bot-protection-tool.vercel.app/bot-protection-gtm.js" async></script>
```
