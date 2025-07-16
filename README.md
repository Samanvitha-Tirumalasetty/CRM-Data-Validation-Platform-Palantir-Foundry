# CRM Application Using Palantir Foundry

## 📌 Overview

This project showcases a CRM (Customer Relationship Management) application built using **Palantir Foundry**, developed as part of a work sample test for Axis Data. The solution translates real-world business needs into a functional, interactive, and scalable CRM system using Foundry's powerful data infrastructure and Ontology tools.

The application helps sales and operations teams manage and analyze relationships between people (contacts) and companies (clients or leads), leveraging data modeling, ETL, and interactive dashboards.

---

## 🧼 Data Cleaning & Transformation

- Cleaned and normalized fields such as emails, phone numbers, and company names.
- Removed duplicate records using distinct and trim operations.
- Standardized text casing and formats.
- Performed ETL on the given datasets to prepare for Ontology modeling.

---

## 🧱 Data Modeling

Two Object Types were created:

- **Person**:
  - Fields: Name, Email, Phone Number, Job Title, Company.
- **Company**:
  - Fields: Name, Address, Revenue, Industry, Website.

A **Link Type** was established between Person and Company using the company name as a foreign key to normalize the model and maintain referential integrity.

---

## 📊 Interactive CRM Dashboard (Ontology View)

The CRM application includes an intuitive and interactive Ontology-based dashboard:

- **Top Section**: Pie chart for segmenting people by job title (or other dimensions like company or industry).
- **Center Section**: Object table showing names, emails, titles, companies, and phone numbers.
- **Right Panel**: Dynamic filters for quick lookup and segmentation by name, title, or company.
- **Profile View**: Clicking on a person opens a detail card, displaying contact information and associated company.

---

## 🚀 Future Enhancements

This CRM framework is designed to be extensible. Possible future upgrades include:

- Integration of deals, opportunity stages, and contact lifecycle.
- Dashboards for high-value clients or industry-specific insights.
- Automated alerts and scheduled pipeline refreshes.

---

## ✅ Conclusion

This CRM application highlights the strength of Palantir Foundry for:

- End-to-end ETL and data modeling.
- Scalable object and relationship management.
- Real-time, interactive dashboards for business users.

The result is a modern CRM tool that closely mirrors enterprise systems like Salesforce or HubSpot, enabling powerful insights and customer relationship tracking in a data-driven environment.

---

## 🛠️ Technologies Used

- **Palantir Foundry** – Data pipelines, Ontology framework, interactive dashboards.
- **ETL Techniques** – Data cleaning, normalization, object modeling.
