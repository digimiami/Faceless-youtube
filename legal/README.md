# Legal Pages Overview

**For: Faceless YouTube Starter Pack**

This folder contains all legal pages required for your digital product business.

---

## Required Pages

### 1. Privacy Policy (`PRIVACY-POLICY.md`)
**Where to display:** Footer of sales page, checkout page
**Why needed:** Required by law (GDPR, CCPA, etc.)
**Key sections:** Data collection, usage, cookies, user rights

### 2. Terms of Service (`TERMS-OF-SERVICE.md`)
**Where to display:** Footer of sales page, checkout page
**Why needed:** Protects your business, sets user expectations
**Key sections:** License terms, refund policy, limitations

### 3. Refund Policy (`REFUND-POLICY.md`)
**Where to display:** Sales page, checkout page, FAQs
**Why needed:** Builds trust, required by Gumroad/Stripe
**Key sections:** 30-day guarantee, process, exceptions

### 4. Earnings Disclaimer (`EARNINGS-DISCLAIMER.md`)
**Where to display:** Sales page (prominently), footer
**Why needed:** Protects against false expectation claims
**Key sections:** No guarantees, typical results, your responsibility

### 5. Cookie Policy (`COOKIE-POLICY.md`)
**Where to display:** Cookie banner, footer
**Why needed:** Required by GDPR and similar laws
**Key sections:** Cookie types, how to manage them

---

## How to Customize

### Replace Placeholders
Find and replace these in all files:
- `[yourdomain].com` → Your actual domain
- `[Your State/Country]` → Your jurisdiction
- `support@[yourdomain].com` → Your support email

### Add to Your Sales Page

Add this to your `sales-page/index.html` footer:

```html
<div style="text-align: center; padding: 20px; font-size: 0.9rem;">
    <a href="legal/PRIVACY-POLICY.html">Privacy Policy</a> | 
    <a href="legal/TERMS-OF-SERVICE.html">Terms of Service</a> | 
    <a href="legal/REFUND-POLICY.html">Refund Policy</a> | 
    <a href="legal/EARNINGS-DISCLAIMER.html">Earnings Disclaimer</a> | 
    <a href="legal/COOKIE-POLICY.html">Cookie Policy</a>
</div>
```

### Convert to HTML

Use the same HTML converter script to convert these to HTML:

```bash
python convert_to_html.py legal/PRIVACY-POLICY.md legal-html/PRIVACY-POLICY.html
```

---

## Legal Disclaimer

**Important:** These templates are provided as a starting point. They are not legal advice.

**You should:**
- Review with a lawyer if possible
- Customize for your specific business
- Update regularly as laws change
- Ensure compliance with your local regulations

**These templates cover:**
- Basic privacy requirements
- Standard terms for digital products
- FTC compliance basics
- GDPR/CCPA basics

---

## Quick Setup Checklist

- [ ] Customize all `[placeholders]`
- [ ] Add your contact information
- [ ] Review and adjust refund period if needed
- [ ] Add links to sales page footer
- [ ] Set up cookie consent banner (if required in your region)
- [ ] Save final versions as HTML
- [ ] Upload to your website/hosting

---

## Recommended Next Steps

1. **Customize these pages** with your specific details
2. **Convert to HTML** using the converter script
3. **Add to your sales page** footer
4. **Set up Gumroad** to link to these pages
5. **Consider legal review** if budget allows

---

**Questions about legal compliance?**

Consult with a qualified attorney in your jurisdiction.

**Questions about these templates?**

Email: support@[yourdomain].com
