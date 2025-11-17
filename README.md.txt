# Cyber Security Internship – Task 2: Phishing Email Analysis

**Name**: Abhyas Kathuria 
**Date**: 17 November 2025

## Task Completed
- Obtained real-world phishing sample (Google Drive Org Chart scam)
- Analyzed full email headers using free online analyzer
- Identified 6 clear phishing indicators (spoofing, fake path, urgency, etc.)
- Created detailed report with evidence

## Files
- `phishing_email.txt` → raw email + headers
- `report.md` → complete analysis table
- `header_analysis.png` → proof of header check

**Outcome achieved**: Learned how attackers abuse legitimate Google domains and how to spot them using header analysis.

Ready for submission!

## Interview Prep

1. **What is phishing?**  
   Deceptive attempt to steal sensitive info (e.g., logins) by posing as trusted sources like Google Drive shares.

2. **How to identify a phishing email?**  
   Spoofed details, urgent tones, mismatched/hover URLs, header fails (SPF/DKIM), grammar slips.

3. **What is email spoofing?**  
   Faking sender identity (e.g., legit @google.com with fake "shared by" name) to impersonate authorities.

4. **Why are phishing emails dangerous?**  
   Enable credential theft, malware spread, or org-wide breaches—e.g., 54% success in Drive scams.

5. **How can you verify the sender’s authenticity?**  
   Check headers for auth passes; log in via official app/site; confirm with sender via known channel.

6. **What tools can analyze email headers?**  
   MX Toolbox, DNSChecker—flag SPF/DKIM/DMARC fails in seconds.

7. **What actions on suspected phishing?**  
   Don't click; report via Gmail "Report Phishing"; block sender; scan device; notify IT.

8. **How do attackers use social engineering in phishing?**  
   Exploit trust/emotion (e.g., "job changes impact you" for fear/curiosity) to override caution.