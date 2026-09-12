# Henrique Ricieri

QA Analyst · Test Automation · C# and JavaScript

<a href="https://www.linkedin.com/in/henriquericieri"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:123ricierihenrique@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>

## About

I test the financial module of an ERP at **Atak Sistemas** in Maringá, Brazil. The product runs food industry companies (meat packers, dairies, tanneries), and my area covers accounts payable and receivable, bank reconciliation, cash flow, boleto payment slips, financial reports, and the bank integrations that run over APIs, including Pix, Brazil's instant payment system.

A bug in that module does not break a layout. It moves money, or fails to move it. So I do not stop at the screen: I run the payment flow the way a user would, read what the bank actually returned in the integration log when it fails, hit the endpoint from **Postman** to isolate the failure, and query **SQL Server** to confirm that the transaction, the balance and the ledger entries match the business rule.

The ERP is being rewritten screen by screen, from an ExtJS front end to Razor Pages on .NET 8. For each migrated screen I write the **Cypress** coverage, check that it behaves exactly like the screen it replaces, and retire the obsolete spec so the suite never carries dead tests.

Before QA I spent a little over a year in support at the same company, reproducing customer-reported defects and isolating the business rule that failed. That is where the domain knowledge comes from.

## Projects

### [LabelForge](https://github.com/HenriqueRicieri/LabelForge)

C# / .NET 10 · Avalonia UI · MIT

A desktop app to design Zebra labels on a canvas and generate ZPL, plus a live viewer that renders ZPL fully offline. Zoom and pan, millimeter rulers, alignment guides and snapping, multi-selection and groups, undo and redo, anchored resize handles and rotation snapping; text, barcode, QR, Data Matrix, image (with dithering), box, ellipse and line elements; a built-in catalog of 797 Zebra media specs; export to ZPL, PNG and PDF at exact physical size; printing over TCP 9100 or the Windows spooler. Packaged as a Windows installer with Velopack.

It is also where I do my testing work in the open. More than 1,000 automated tests run in CI on every push, and a headless end-to-end harness I wrote from scratch (`tools/LabelForge.E2E`) drives the real designer, simulates pointer input on the canvas and rulers, checks the expected values, captures screenshots in both themes and fails the build through its exit code.

### [cypress-e2e-saucedemo](https://github.com/HenriqueRicieri/cypress-e2e-saucedemo)

JavaScript · Cypress 15 · GitHub Actions

End-to-end suite for the SauceDemo store: login, inventory, cart and checkout, built with Page Objects, a custom `cy.loginAs()` command and fixtures. A CI workflow runs the whole suite on every push and keeps the screenshots when something fails.

## Tools

<div align="center">

![Cypress](https://img.shields.io/badge/Cypress-69D3A7?style=for-the-badge&logo=cypress&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=csharp&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

</div>

At work: Cypress, JavaScript, SQL Server, Postman, Git, GitLab and GitHub Actions, testing an ExtJS front end and Razor Pages on .NET 8. Own projects: C#, .NET 10, Avalonia UI, xUnit, SkiaSharp and Velopack.

## Background

- Degree in Systems Analysis and Development, UniCesumar (2022 to 2024)
- English at C1 level, certified by the Michigan English Test (MET)

## Stats

<div align="center">
  <img src="https://github-readme-stats-beta-umber.vercel.app/api?username=HenriqueRicieri&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub stats"/>
  <img src="https://github-readme-stats-beta-umber.vercel.app/api/top-langs/?username=HenriqueRicieri&layout=compact&theme=tokyonight&hide_border=true&hide=zimpl" alt="Top languages"/>
</div>

<div align="center">
  <img src="https://github-readme-streak-stats-ricieri.vercel.app/?user=HenriqueRicieri&theme=tokyonight&hide_border=true" alt="Contribution streak"/>
</div>
