# Cloud-based-Order-Tracking-System


# Order Tracking System ☁️📦

A cloud-native, microservices-based order tracking system using:
- .NET 8 Web APIs
- AWS EKS (Kubernetes)
- ECS Fargate (Background workers)
- AWS Lambda (Email notifications)
- Raven API (mock CRM integration)
- PostgreSQL (RDS)
- Terraform (Infrastructure as Code)

## 🧩 Microservices
- `OrderService`: Receives and stores customer orders.
- `StatusService`: Updates order shipping status.

## 🚀 Goals
- Containerized microservices running on EKS
- Async status updater via ECS task
- Email notification on shipment via Lambda
- Real-time external sync with CRM API
- Full infrastructure provisioned with Terraform

## 📅 Timeline
This project is broken into a 2-week plan. Day 1: scaffold code and structure (YOU ARE HERE ✅)

## 📂 Folder Structure
order-tracking-system/
├── infra/ # Terraform code
├── services/
│ ├── OrderService/ # .NET API
│ └── StatusService/ # .NET API
├── lambdas/ # Lambda functions
├── ecs-worker/ # ECS container task
└── README.md

