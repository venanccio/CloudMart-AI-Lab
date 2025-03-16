Contributing to CloudMart AI
Thank you for your interest in contributing to CloudMart AI! We welcome contributions of all kinds, including bug fixes, feature enhancements, documentation improvements, and more. This guide will help you get started and ensure a smooth collaboration process.

📋 Table of Contents
How to Contribute

Code of Conduct

Getting Started

Development Environment Setup

Submitting Issues

Submitting Pull Requests (PRs)

Coding Guidelines

Commit Message Guidelines

Recognition

Where to Get Help

How to Contribute
We welcome contributions in the following areas:

Bug Reports: Found a bug? Let us know by opening an issue.

Feature Requests: Have an idea for a new feature? Share it with us!

Code Contributions: Submit a pull request (PR) with your code changes.

Documentation: Help improve our docs by correcting typos, clarifying instructions, or adding new content.

Testing: Test the project and report any issues or suggest improvements.

Code of Conduct
We are committed to fostering an open and welcoming environment. Please be respectful in all interactions and follow our Code of Conduct.

Getting Started
Development Environment Setup
To contribute to CloudMart AI, follow these steps:

Clone the Repository:

bash
git clone https://github.com/yourusername/cloudmart-ai.git
cd cloudmart-ai
Set Up Cloud Provider Credentials:
Ensure you have access to AWS, Azure, and Google Cloud accounts with appropriate permissions.

Install Prerequisites:

Terraform

Docker

kubectl

AWS CLI

Provision Infrastructure:

bash
cd terraform-project
terraform init
terraform plan
terraform apply
Deploy Applications:

bash
aws eks update-kubeconfig --name cloudmart --region us-east-1
kubectl apply -f cloudmart-backend.yaml
kubectl apply -f cloudmart-frontend.yaml
Run tests locally before submitting your changes.

Submitting Issues
If you encounter a bug or have a feature request:

Search the issue tracker to see if it has already been reported.

If not, create a new issue with:

A clear title.

A detailed description of the problem or feature.

Steps to reproduce (for bugs).

Any relevant screenshots or logs.

Submitting Pull Requests (PRs)
To contribute code:

Fork the repository and create your branch:

bash
git checkout -b feature/your-feature-name
Make your changes following the coding guidelines below.

Test your changes locally.

Commit your changes (see commit message guidelines below).

Push your branch:

bash
git push origin feature/your-feature-name
Open a pull request on the main repository with:

A clear description of your changes.

Links to relevant issues (if applicable).

Coding Guidelines
Please adhere to the following guidelines:

Follow the existing project structure and naming conventions.

Use consistent formatting (e.g., 2-space indentation for YAML files).

Write clear, concise comments where necessary.

Ensure all code is properly tested before submission.

For specific coding standards, refer to the style guides in the respective directories (backend/, frontend/, etc.).

Commit Message Guidelines
Use clear and descriptive commit messages formatted as follows:

Format: <type>(<scope>): <description>
Example: feat(backend): add product recommendation endpoint

Types:

feat: A new feature.

fix: A bug fix.

docs: Documentation updates.

style: Code style changes (non-functional).

refactor: Code restructuring without changing behavior.

test: Adding or updating tests.

chore: Maintenance tasks (e.g., dependency updates).

Recognition
We deeply value our contributors! All contributors will be recognized in our project documentation and release notes.

Where to Get Help
If you have questions or need assistance:

Check our README.md for setup instructions and project details.

Review open issues in the issue tracker.

Reach out via our communication channels (e.g., Slack or Email: venanccio.rodrigo@gmail.com).

Thank you for contributing to CloudMart AI! 🎉