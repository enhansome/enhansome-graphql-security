<!--lint disable awesome-list-item awesome-toc-->

# Awesome GraphQL Security with stars

A curated list of awesome GraphQL Security frameworks, libraries, software, and resources.

## Contents

* [Defensive Security](#defensive-security)
  * [Authentication & Authorization](#authentication--authorization)
  * [Continous Security Testing](#continous-security-testing)
  * [Middlewares](#middlewares)
  * [Security Solutions](#security-solutions)
* [Neutral Security](#neutral-security)
  * [Clients and IDEs](#clients-and-ides)
  * [Self-Discovery](#self-discovery)
  * [Visualizers](#visualizers)
* [Offensive Security](#offensive-security)
  * [Discovery](#discovery)
  * [Exploitation](#exploitation)
  * [Vulnerable Applications](#vulnerable-applications)
* [Resources](#resources)
  * [Blogs](#blogs)
  * [Vulnerabilities](#vulnerabilities)

## Defensive Security

### Authentication & Authorization

* [GraphQL Shield](https://github.com/maticzav/graphql-shield) ⭐ 3,578 | 🐛 107 | 🌐 TypeScript | 📅 2026-08-14 - Helps you create a permission layer for your application.
* [GraphQL Authz](https://github.com/AstrumU/graphql-authz) ⭐ 197 | 🐛 24 | 🌐 TypeScript | 📅 2024-08-12 - GraphQL authorization layer

### Continous Security Testing

* [GraphQL Cop](https://github.com/dolevf/graphql-cop) ⭐ 687 | 🐛 4 | 🌐 Python | 📅 2025-11-20 - Utility to run common security tests against GraphQL APIs that can be run inside CI/CD.
* [Escape - GraphQL Security](https://escape.tech) - Continuous GraphQL Security Testing for Developers. Find and fix GraphQL security flaws in the CI/CD.

### Middlewares

* [GraphQL Armor](https://github.com/Escape-Technologies/graphql-armor) ⭐ 586 | 🐛 37 | 🌐 TypeScript | 📅 2026-08-22 - Highly customizable security middleware for Apollo GraphQL and Envelop servers.

### Security Solutions

* [WAF for GraphQL](https://lab.wallarm.com/api-security-solution/) - Web Application Firewall for GraphQL APIs.

## Neutral Security

### Clients and IDEs

* [Hoppscotch](https://github.com/hoppscotch/hoppscotch) ⭐ 80,090 | 🐛 803 | 🌐 TypeScript | 📅 2026-08-24 - Online REST and GraphQL client
* [Postman](https://www.postman.com/) - An API platform for developers to design, build, test and iterate their APIs.
* [Insomnia](https://insomnia.rest/) - Design and test GraphQL APIs with ease.
* [Altair](https://altairgraphql.dev/) - GraphQL Client helps you debug GraphQL queries and implementations. Also distributed as a Browser Extension.

### Self-Discovery

* [GraphMan](https://github.com/Escape-Technologies/graphman) ⭐ 252 | 🐛 7 | 🌐 TypeScript | 📅 2024-08-26 - Generate a complete Postman collection from a GraphQL endpoint. Allows instant and easy discovery and exploration of the API.

### Visualizers

* [Voyager](https://github.com/IvanGoncharov/graphql-voyager) ⭐ 8,161 | 🐛 106 | 🌐 TypeScript | 📅 2026-05-12 - Represent any GraphQL API as an interactive graph.
* [GraphQL Inspector](https://github.com/kamilkisiela/graphql-inspector) ⭐ 1,759 | 🐛 139 | 🌐 TypeScript | 📅 2026-08-20 – Validate schema, get schema change notifications, validate operations, find breaking changes, look for similar types, schema coverage.
* [GraphQL Rover](https://github.com/Brbb/graphql-rover) ⭐ 264 | 🐛 9 | 🌐 JavaScript | 📅 2023-09-25 - GraphQL schema viewer for endpoints with introspection
* [CraftQL](https://github.com/yamafaktory/craftql) ⭐ 113 | 🐛 0 | 🌐 Rust | 📅 2023-05-18 - CLI GraphQL schema viewer, view schema diagram on the terminal or generate graphviz .dot format file

## Offensive Security

### Discovery

* [Clairvoyance](https://github.com/nikitastupin/clairvoyance) ⭐ 1,507 | 🐛 42 | 🌐 Python | 📅 2025-12-05 - Patrial introspection fetcher when introspection is disabled.
* [Graphw00f](https://github.com/dolevf/graphw00f) ⭐ 890 | 🐛 3 | 🌐 Python | 📅 2026-05-16 - GraphQL Server Engine Fingerprinting utility.
* [Graphinder](https://github.com/Escape-Technologies/graphinder) ⭐ 228 | 🐛 6 | 🌐 Python | 📅 2023-05-22 - Blazing fast GraphQL endpoints finder using subdomain enumeration, scripts analysis and bruteforce.
* [Goctopus](https://github.com/Escape-Technologies/goctopus) ⭐ 134 | 🐛 3 | 🌐 Go | 📅 2023-11-21 - a GraphQL endpoint discovery and fingerprinting tool.
* [ShapeShifter](https://github.com/szski/shapeshifter) ⭐ 125 | 🐛 3 | 🌐 Python | 📅 2022-03-31 - Schema extraction to JSON file with introspection.
* [GraphQL Path Enum](https://gitlab.com/dee-see/graphql-path-enum) – Tool that lists the different ways of reaching a given type in a GraphQL schema.

### Exploitation

* [InQL](https://github.com/doyensec/inql) ⭐ 1,801 | 🐛 30 | 🌐 Kotlin | 📅 2026-06-17 - A Burp Extension for GraphQL Security Testing.
* [GraphQLMap](https://github.com/swisskyrepo/GraphQLmap) ⭐ 1,687 | 🐛 20 | 🌐 Python | 📅 2024-03-11 - A scripting engine to interact with a GraphQL endpoint for pentesting purposes.
* [GraphQL wordlist](https://github.com/Escape-Technologies/graphql-wordlist) ⭐ 484 | 🐛 1 | 🌐 TypeScript | 📅 2023-10-03 - the only GraphQL wordlist for pentesting you'll ever need. Operations, field names, type names. It was collected on more than 60k distinct GraphQL schemas.
* [BatchQL](https://github.com/assetnote/batchql) ⭐ 413 | 🐛 5 | 🌐 Python | 📅 2022-12-24 - GraphQL security auditing script with a focus on performing batch GraphQL queries and mutations.
* [GraphQL Threat Matrix](https://github.com/nicholasaleks/graphql-threat-matrix) ⭐ 369 | 🐛 9 | 📅 2025-07-01 - GraphQL threat framework to research security gaps in GraphQL implementations.
* [CrackQL](https://github.com/nicholasaleks/CrackQL) ⭐ 350 | 🐛 0 | 🌐 Python | 📅 2024-08-03 - GraphQL password brute-force and fuzzing utility.
* [GraphCrawler](https://github.com/gsmith257-cyber/GraphCrawler) ⚠️ Archived - A GraphQL automated security toolkit. Grab introspection, search for sensitive queries, and then test authorization.
* [GraphQL.Security](https://graphql.security) - One-click quick security scan of your GraphQL endpoints. Free, no login required.

### Vulnerable Applications

* [Damn Vulnerable GraphQL Application](https://github.com/dolevf/Damn-Vulnerable-GraphQL-Application) ⭐ 1,705 | 🐛 3 | 🌐 JavaScript | 📅 2025-05-24 - An intentionally vulnerable implementation of Facebook's GraphQL technology, to learn and practice GraphQL Security.

## Resources

### Blogs

* [Access Control Best Practices for GraphQL with Authentication and Authorization](https://escape.tech/blog/authentication-authorization-access-control/) - Confusion between authentication and authorization causes data leaks. Learn the difference and how to implement the right access control pattern in your GraphQL API.
* [Apollo Blog](https://www.apollographql.com/blog/graphql/security/9-ways-to-secure-your-graphql-api-security-checklist/) - Take your GraphQL skills to the next level with our free interactive GraphQL tutorials, videos, quizzes and code challenges.
* [The GraphQL Security Blog](https://escape.tech/blog/9-graphql-security-best-practices/) - Learn about GraphQL security, performance, testing and building production-ready APIs with the latest tools and best practices of the GraphQL ecosystem.
* [GraphQL for Pentesters](https://www.acceis.fr/graphql-for-pentesters/) - Introduction to Basic Concepts, Security Considerations & Reconnaissance, Vulnerabilities and Attacks, Offensive Tools.
* [GraphQL security for decentralized applications (DApps): challenges and best practices](https://escape.tech/blog/graphql-security-for-dapps/) - Learn about GraphQL security, performance, testing and building production-ready APIs with the latest tools and best practices of the GraphQL ecosystem.
* [Implementing GraphQL Authorization: A Practical Guide](https://www.permit.io/blog/implementing-graphql-authorization) - Learn how to implement scalable authorization in GraphQL. Simplify RBAC and Permissions management with step-by-step instructions.

## Papers

* [Enhancing GraphQL Security by Detecting Malicious Queries Using Large Language Models, Sentence Transformers, and Convolutional Neural Networks](https://www.researchgate.net/publication/394539388_Enhancing_GraphQL_Security_by_Detecting_Malicious_Queries_Using_Large_Language_Models_Sentence_Transformers_and_Convolutional_Neural_Networks)

### Vulnerabilities

* [Aliasing Attacks](https://escape.tech/blog/graphql-batch-attacks-cause-dos/) - Addressing the Security concerns of GraphQL Aliases.
* [File Inclusion and Directory Traversal](https://escape.tech/blog/file-inclusion-directory-traversal-graphql/) - Reading arbitrary server files through unvalidated path parameters in GraphQL.
* [GraphQL CSRF](https://escape.tech/blog/understanding-and-dealing-with-cross-site-request-forgery-attacks/) - Understanding and Dealing with Cross-Site Request Forgery Attacks (CSRF) in GraphQL.
* [GraphQL Cyclic Queries and Depth Limiting](https://escape.tech/blog/cyclic-queries-and-depth-limit/) - The relational aspect of GraphQL can be a vulnerability exploited by running deep and cyclic queries causing your API to crawl under the load and crash.
* [HTTPS and GraphQL](https://escape.tech/blog/prevent-data-leaks-with-https/) - How HTTPS can prevent Data Leaks.
* [SQL Injection](https://escape.tech/blog/sql-injection-in-graphql/) - SQL Injections in GraphQL.
* [Verbose Errors Suggestions](https://escape.tech/blog/graphql-verbose-error-suggestions/) - When GraphQL Error Messages become a Security Issue.
* [What are Insecure Direct Object References (IDOR) in GraphQL, and how to fix them](https://escape.tech/blog/idor-in-graphql/) - When GraphQL Error Messages become a Security Issue.

## Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/Escape-Technologies/awesome-graphql-security/blob/main/CONTRIBUTING.md) ⭐ 397 | 🐛 2 | 📅 2026-07-16 first.

We will keep some pull requests open if we are not sure whether those libraries are awesome, you could [vote for them](https://github.com/Escape-Technologies/awesome-graphql-security/pulls) ⭐ 397 | 🐛 2 | 📅 2026-07-16 by adding :+1: to them.

***

If you have any question about this opinionated list, do not hesitate to contact us [@escapetechHQ](https://twitter.com/escapetechHQ) on Twitter or open an issue on GitHub.

## 🤝 Join our team

We believe it's time to bring more AI-driven innovation to cybersecurity, and we'd love your help in building this dream! Want to join our adventure? Check out our [**Careers**](https://jobs.escape.tech) page!

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-24._
