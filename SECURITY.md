# Security

At Koninklijke Ahold Delhaize N.V. (“Ahold Delhaize”) we are committed to maintaining the security of our systems and data. We believe that good security is critical to the trust of customers, suppliers and employees. As such we strive to continuously improve our security and welcome your help in this perspective.

## Enhancement of data and system security at Ahold Delhaize

If you have found a weak spot in one of our systems, we would like to hear about this from you directly, so the necessary measures can be taken as quickly as possible to enhance system security. In order to enhance system security responsibly, we kindly draw your attention to the following.

## Ahold Delhaize kindly asks you

* to e-mail your findings to ad.itsecurity.group@aholddelhaize.com
* to provide sufficient information to reproduce the problem, so that Ahold Delhaize can address it as quickly as possible. The IP address or the URL of the system affected and a description of the findings are usually sufficient, but more may be needed for more complex findings.
* to report your findings as quickly as possible after its discovery.
* not to share any information on the findings with any other party than designated persons at Ahold Delhaize.
* to handle the knowledge on the findings with care by not performing any acts other than those necessary to reveal the findings.

## We expect you not to

* install malware.
* copy, change or delete data in a system (an alternative to this is making a directory listing of a system).
* make changes to a system.
* repeatedly access the system or share access with others than designated persons at Ahold Delhaize.
* use so-called “brute force” to access systems.
* use denial-of-service or social engineering.
* perform any action that might potentially have a disruptive effect on our systems.

## What you can expect

* Ahold Delhaize does not share your personal details with third parties without your permission, unless this is mandatory by law or regulation.
* Only after mutual consultation, your name can be mentioned as the person who made the findings.
* Ahold Delhaize will send you a confirmation of receipt as soon as reasonably possible.
* Ahold Delhaize offers a reward as thanks for help. Depending on the seriousness of the findings and the quality of the report, the reward can vary from a T-shirt, a meet & greet with our IT security team, to a maximum EUR 300 in gift vouchers. It must at least concern a serious finding that is unknown to us.

## Out of scope vulnerabilities

When reporting vulnerabilities, please consider the attack scenario and security impact. The following types of vulnerabilities are considered out of scope and not eligible for a reward in our Program:

* Clickjacking on pages with no sensitive actions and without a documented series of clicks that can exploit a sensitive functionality
* CSRF for non-significant actions
* CORS misconfigurations when the Credentials header is not set
* Missing HTTP security Headers that do not directly lead to a vulnerability, such as:
  * Content-Security-Policy
  * Strict Transport Security
  * X-Content-Type-Options
  * X-XSS-Protection
  * X-Frame-Options (unless there is a well-defined risk)
  * X-Download-Options
  * X-XSS-Protection
  * Feature/Permissions Policy
* Missing best practices in SSL/TLS configuration
* Missing best practices in Content Security Policy
* Missing email best practices (Invalid, incomplete or missing SPF/DKIM/DMARC records, etc.)
* Missing cookie flags on cookies that do not hold session or other sensitive information
* Information Disclosure – default exposed config files with no sensitive data
* Open redirect vulnerabilities that do not demonstrate additional security impact
* Content spoofing and text injection issues without showing an attack vector or being able to modify HTML/CSS
* Host header Injection with no demonstrable impact
* Vulnerabilities reported shortly after their public release
* Exposed Google maps API keys that cannot be misused due to implemented restrictions
* Vulnerability reports from automated tools without validation
* Denial of Service and Social Engineering attacks
* Attacks requiring MITM or physical access to a user's device
