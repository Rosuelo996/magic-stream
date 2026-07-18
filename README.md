MagicStream

A full-stack movie recommendation platform built with React, Go, MongoDB, OpenAI, and Docker that provides AI-powered movie recommendations and secure user authentication.

About

This project demonstrates how a React frontend communicates with a Go backend to deliver a modern movie recommendation platform. The backend manages authentication, movie data, and AI-powered recommendations, while MongoDB stores application data. The project also showcases containerization with Docker, CI/CD automation, and production deployment.

Features
AI-powered movie recommendations using OpenAI
User registration and JWT authentication
Access and refresh token authentication
Go REST API built with the Gin framework
React frontend consuming backend API endpoints
MongoDB integration for application data
Docker and Docker Compose for development and production
GitHub Actions CI/CD pipeline
Docker Hub image publishing
Production deployment with Hostinger
Environment variables for secure configuration
Error handling and request validation
Tech Stack
React
Go
Gin
MongoDB
Docker
Docker Compose
GitHub Actions
OpenAI API
LangChainGo
JavaScript
HTML
CSS
Getting Started

Install dependencies and start the development environment:

docker compose -f docker-compose.dev.yaml up --build

Or run the frontend and backend separately by following their respective setup instructions.

Purpose

This repository was created to practise building and deploying a production-ready full-stack application using React, Go, MongoDB, Docker, CI/CD pipelines, and AI integration while following modern development and deployment workflows.
