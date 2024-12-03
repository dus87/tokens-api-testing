# tokens-api-testing

Test suite for /tokens endpoint
# 🚀 API Testing Suite for `/tokens` endpoint

A comprehensive testing suite for [li.fi](https://apidocs.li.fi/reference/get_v1-tokens)  `/tokens` endpoint using Postman collections.
This suite ensures reliability, performance, and security of the token-related services.

## 📚 Table of Contents
- [Overview](#overview)
- [Test Categories](#test-categories)
- [Setup](#setup)
- [Running Tests](#running-tests)
- [Test Reports](#test-reports)

## 🎯 Overview

This testing suite validates the Token API's functionality, covering various scenarios.
The suite is designed to ensure the API maintains high quality and reliability standards.

### 🌟 Key Features
- Comprehensive test coverage
- Automated validation
- Detailed error reporting
- Performance monitoring
- Security validation

## 🔍 Test Categories

### 1. Basic Response Tests
- Status code validation
- Response format verification
- Required field validation

### 2. Parameter Testing
- Chain parameter validation
- Price parameter validation
- Edge case handling

### 3. Chain Parameter Tests
- Valid chain types
- Invalid chain scenarios
- Cross-chain validation

### 4. Security Tests
- SQL injection prevention
- XSS vulnerability checks
- Rate limiting validation

### 5. Performance Tests
- Response time validation
- Load testing scenarios
- Spike test validation

## 💻 Setup

1. Clone the repository

`git clone` https://github.com/dus87/tokens-api-testing.git

2. Import the Postman collection
- Open Postman
- Click "Import"
- Select the collection file in collections/tokens_api_tests.postman_collection.json

## ▶️ Running Tests

### Using Postman UI
1. Open the collection in Postman
2. Select desired environment
3. Click "Run Collection"

### Using Newman (CLI)

`newman run tokens_api_tests.postman_collection.json`

### Using Github Actions
Tests are automatically run on pull requests to the `main` branch to ensure API reliability before merging changes.

### Running Tests Locally
`npm install`
`npm run test`

## 📊 Test Reports

Test reports are automatically generated after each run, providing:
- Total tests executed
- Pass/Fail ratio
- Response times
- Error details


## 🛠️ Built With
- Postman
- Newman
- JavaScript
- GitHub Actions
