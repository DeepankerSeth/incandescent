# Jan Adhikar / जन अधिकार

A privacy-first, nonpartisan civic action and legal-information toolkit for people in India.

## Purpose

Jan Adhikar helps a person:

- choose the official route that matches their situation;
- prepare an individualized, fact-based complaint or representation;
- preserve original evidence safely;
- request legal aid;
- generate an RTI application for identifiable central-government records;
- prepare a witness statement or custody inquiry; and
- understand the difference between an email, an administrative complaint and a formal court filing.

It is not a law firm, emergency service, court-filing service, petition-signing campaign, evidence repository or substitute for individualized legal advice.

## Privacy design

- No login or account.
- No analytics, cookies or advertising.
- No backend and no database.
- Form entries are processed entirely in the browser.
- The site does not upload or retain evidence.
- Language preference is the only value stored locally.
- The service worker allows core pages and templates to work offline after the first successful visit.

Users should still avoid entering sensitive information on a shared or compromised device.

## Safety and integrity principles

1. State only facts personally known to the sender.
2. Clearly identify information learned from another person or public report.
3. Do not falsely claim to be a victim, witness, lawyer or representative.
4. Do not publish identity documents, medical records, home addresses, detainee details or vulnerable people’s faces.
5. Preserve untouched originals and use redacted copies for public sharing.
6. Do not name an alleged perpetrator without supportable identification.
7. Do not coordinate identical mass submissions. Individualized, truthful complaints are more useful.
8. Do not delay emergency, medical or legal assistance while preparing a document.
9. Disclose related legal proceedings and avoid duplicative court filings.
10. Correct material errors promptly and transparently.

## Included generators

- National Human Rights Commission complaint
- Delhi Police Vigilance complaint
- Supreme Court PIL/letter-petition representation
- SCLSC/DSLSA legal-aid request
- NEET (UG) candidate grievance
- Central RTI request
- Factual witness statement
- Custody/whereabouts inquiry

## Official sources

Contact details were checked against official public websites on 22 July 2026. Government contacts and procedures can change. Recheck before a large campaign or public launch.

Primary sources linked from the website include:

- Supreme Court of India contact, jurisdiction and e-Filing pages
- Supreme Court Legal Services Committee
- National Human Rights Commission complaint guidance and HRCNet
- Delhi Police contact directory and citizen portal
- Delhi State Legal Services Authority
- CPGRAMS
- RTI Online
- National Testing Agency / NEET

## Deployment

The repository contains a GitHub Pages workflow at `.github/workflows/pages.yml`. The static site is stored as eight base64-encoded bundle segments in `.site-bundle/`. During deployment, GitHub Actions reconstructs the archive, checks its SHA-256 digest, extracts it, verifies the core files, and publishes the result.

For first-time publication:

1. Open the repository’s **Settings**.
2. Open **Pages**.
3. Under **Build and deployment**, choose **GitHub Actions** as the source.
4. Push to `main` or manually run the workflow.

The project is a static site and can also be deployed to Cloudflare Pages, Netlify, Vercel or any ordinary web server without a build command.

## Updating official contacts

Before changing a contact:

1. Verify it on the authority’s official `.gov.in`, `.nic.in` or official institutional website.
2. Prefer a dedicated complaint portal over a general email.
3. Record the verification date in the site and this README.
4. Test every telephone, email, portal and mailing address.
5. Have an Indian lawyer review any change to legal claims or generated text.

## Recommended pre-launch review

Before distributing the site at scale, obtain review from:

- an Indian constitutional lawyer;
- a Supreme Court Advocate-on-Record for the Article 32/PIL pathway;
- a Delhi lawyer for detention, police-action and Article 226 pathways;
- a digital-security specialist for activist and witness safety; and
- a Hindi legal-language reviewer.

## License and reuse

This package is intended for public-interest use. Before broad third-party reuse, select and add an appropriate open-source license and identify the responsible maintainer and correction channel. Do not remove safety warnings or make the site appear to be an official government service.

## Repository history

This repository previously contained only the README text “incandescent — CS 4555 Team 14 Github repository.” That note is preserved here for historical continuity; no prior application files were overwritten.
