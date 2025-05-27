# Task-2
Phishing is a common type of cyberattack in which attackers impersonate legitimate entities to trick users into revealing sensitive information like passwords, banking details, or personal data.In this task, we aim to analyze a sample phishing email and identify the warning signs and suspicious elements that indicate it is not a genuine message. By examining elements such as sender address, content tone, grammar, embedded links, and attachments, we can understand how phishing emails are crafted and learn how to detect and avoid them in real-world situations.

Method Used:
To better understand the structure and signs of a phishing email, I used a free fake email generator website such as CanIPhish to generate a sample phishing email. These tools are designed for learning and simulation purposes.
In the generated email, I carefully examined the email header information, including:

"From" Address – to see if it was spoofed or suspicious.
"To" Address – to check the targeted recipient.
Email Subject & Content – to identify urgency or misleading language.
Email Header – to analyze the email path and sender’s domain.

Analyzing the Email Header:
After receiving the fake phishing email, I copied the email header and pasted it into MXToolbox (https://mxtoolbox.com/EmailHeaders.aspx), a free online tool used for analyzing email headers.

This tool helped me:

Trace the real source of the email (the originating IP and sending server)
Check for any spoofed domains
See the path the email took through various mail servers
Evaluate if SPF, DKIM, or DMARC checks passed or failed

By using MXToolbox, I was able to detect whether the email was spoofed or sent from an unauthorized or suspicious mail server — which is a strong indicator of phishing.

Suspicious Links in the Email:
Upon analyzing the content of the fake phishing email, I noticed that the email contained clickable links disguised as legitimate ones. However, when I hovered over the links (without clicking), I observed that the actual destination URL was completely different from the visible text.

This technique is commonly used in phishing emails to trick users into clicking on malicious links that appear to be safe. These links often lead to:

Fake login pages (to steal credentials)
Malware download sites
Phishing websites mimicking real brands

The mismatch between the displayed link and the actual link is a strong indicator of phishing and poses a significant security risk to users who may unknowingly click on it.

Use of Threatening Language:
The phishing email also contained threatening and alarming language designed to create panic and urgency. For example, it included statements like:

"If someone else has access to your account, they have your password and might be trying to access your personal information or send junk email."

Such messages are intentionally written to make the user feel that their account is at risk. The goal is to pressure the recipient into clicking a malicious link or providing login details without thinking. This social engineering technique is very common in phishing attacks and is a clear red flag.

Spelling and Grammar Check:
Interestingly, the phishing email did not contain any spelling or grammar mistakes, which are often common in such attacks. This shows that some phishing emails can appear very professional and well-written, making them harder to detect based on grammar alone.

This emphasizes the importance of checking other indicators such as sender address, header details, mismatched links, and threatening language, rather than relying only on poor grammar to identify phishing attempts.

The phishing email exhibited several common traits that indicate its malicious nature. Firstly, the links within the email were deceptive; the visible text did not match the actual destination URLs, which led to suspicious or harmful websites. Additionally, the email used threatening and urgent language to create fear, encouraging the recipient to act hastily without verifying the message's authenticity. The sender’s email address appeared suspicious or spoofed, differing from the official domain it claimed to represent. Interestingly, the email was professionally written without any spelling or grammar mistakes, which can make such phishing attempts more convincing and harder to detect based on language quality alone. These combined factors clearly reveal the email’s phishing intent.
