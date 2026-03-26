# AWS Cloud Security Portfolio
> Serverless resume platform built on AWS, hardened the way a security engineer would.

## Live Site
🌐 [damillerjr.me](https://damillerjr.me)

## Architecture
- **Frontend** — Static HTML/CSS hosted on S3, served by CloudFront CDN
- **Backend** — Visitor counter powered by Lambda, DynamoDB, API Gateway
- **Security** — Least-privilege IAM, KMS encryption at rest, CloudTrail audit logging
- **IaC** — Full CloudFormation templates for every resource
- **CI/CD** — GitHub Actions auto-deploys on push to main

## AWS Services Used
`S3` `CloudFront` `Lambda` `DynamoDB` `API Gateway` `IAM` `KMS` `CloudTrail` `CloudWatch` `ACM` `CloudFormation`

## Project Phases
- [x] Week 1 — HTML/CSS resume built and deployed to S3
- [ ] Week 2 — CloudFront + HTTPS + custom domain
- [ ] Week 3 — IAM hardening, KMS encryption, CloudTrail, security documentation
- [ ] Week 4 — Serverless visitor counter (Lambda + DynamoDB + API Gateway)
- [ ] Week 5 — CloudFormation IaC for all resources
- [ ] Week 6 — CI/CD pipeline, architecture diagram, final documentation

## Security Decisions
See [SECURITY.md](./SECURITY.md) for a full writeup of every security decision made 
and why. You will see my IAM scoping, encryption choices, logging strategy, and what I would add in production.

## Local Development
```bash
git clone https://github.com/Darrin07/aws-cloud-resume
cd aws-cloud-resume
# open index.html in your browser
```
