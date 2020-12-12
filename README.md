# teamreviewer
Team Reviewer - defectDojo plugin
Team Reviewer is 100% Web GUI app, based on OWASP Defect Dojo with a lot of enhancements:

- Multi-language Kit is available for localization.

- Direct execution of all features provided by Security Reviewer Suite (SAST, DAST, IAST, SCA, Mobile, Firmware)

- Extended Workflow and Reporting features, GDPR Compliance Level included

- Performant database, based on MariaDB 10.x Galera cluster. It can be changed to Oracle RAC 12 or any other Supported Relational Database

- Secured Source code and Operation platform, due to an accurate Static Code Review and Dynamic Analysis made by Security Reviewer and Dynamic Reviewer tools

- Encryption of DB Tables containing sensitive data (Users, Groups, Applications, Workflow, Policies, etc.)

- SAST, IAST and DAST Integration

- Mobile Behaviorial Analysis integration (Mobile Reviewer)

- Software Composition Analysis (SRA) integration

- Software Resilience Analysis (SCA) Integration

- Firmware Reviewer Single Sign On

- SQALE, OWASP Top Ten 2017, Mobile Top Ten 2016, CWE, CVE, WASC, CVSSv2, CVSSv3.1 and PCI-DSS 3.2.1 Compliance

- Application Portfolio Management tools integration

Getting Started:
git clone https://github.com/DefectDojo/django-DefectDojo
cd django-DefectDojo
git checkout release/1.7.1
git clone https://github.com/dsyman/teamreviewer
docker-compose build
docker-compose up -d
