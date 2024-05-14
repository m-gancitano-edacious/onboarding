# Development

## Planning and Tracking
Why are we doing a project, what are the hard requirements, and what are the nice to haves?

- **How do we know if a project is on track or not?**
- **Is there any cadence for the regular review of project status with stakeholders?**

## Developer Ergonomics
What is our developer experience really like? Can we make it better?

- **How easy is it to get work done from the perspective of an engineer on a team?**
- **Are there any areas where we need to address tech debt?**

## Architectural and Technology Standards
- **Do we have well-defined architectural design patterns we expect all engineers to follow?**
  - For backend, model vs serializer vs view?
  - For data, when is it a hard-code configuration and when is it managed in GEMYN?
  - For frontend, how much do we follow atomic design?

## Security Readiness
What is our current security setup and do we see it getting more serious and when?

- **Do we have standards or guidelines for how to architect secure applications?**
- **Do we do automated vulnerability testing during CI? Static analysis? Dynamic analysis? Open source vulnerabilities? Sonarqube?**
- **Do we do external penetration testing? When was the last test? What were the findings? Is the next test scheduled?**
- **Are we maintianing and/or pursuing compliance with security standards such is ISO 27k, SOC II, GDPR, FedRAMP, etc?**

## Continuous Integration
- **Is all our code always able to build successfully? What is the behavior when a commit fails the build/jobs in the CI?**
  - Do we care about the missing test of eda e2e in gemyn PRs?

## Testing & Quality
- **How much of our testing is manual vs. automated today?**
  - What is the process for testing a new feature? manual vs. automated?
- **Do we collect test data in any consistent and transparent way? Coverage, success rates, etc.? Where?**
  - Are we able to know how much of the app is covered by eda e2e tests?
- **Do we consistently test our APIs against their contracts? Is this automated? Do we use any kind of mocking or service virtualization today to enable component testing of APIs?**
  - Can we automatically test our endpoints via the OpenAPI spec?

## Release & Deployment
- **Do we have any consistent enforcement of what constitutes “done” for making release decisions in terms of quality, security, testing, etc.?**

## Bug Management
Are we properly resolving / stabilizing small fixes / bugs?

- **How are most production bugs discovered?**
- **Do we add tests every time we fix a bug to ensure it doesn’t repeat? How universal is this behavior?**

# People

## Career Management
- **Is there a defined career framework? If not, why? If yes, what are the levels and expectations? Do managers and ICs have access to the expectations? Are they regularly used in career conversations?**

# Business
I moved business velocity and data-driven behavior down here. I guess these can be grouped as a form of 'knowing when business priorities change' from an engineering perspective and are we aligned with those?

## Business Velocity
- **Do we currently measure how many releases or config changes we do that result in a change to customer experience? How often do we push changes to our customers?**

## Data-driven Behavior
- **How does customer satisfaction feed back into company/product priorities?**

## Strategy and Execution
- **What are the current goals/targets/OKRs of the business?**
- **What is the process/cadence for setting/reviewing targets?**

