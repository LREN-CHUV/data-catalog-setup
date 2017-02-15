[![License](https://img.shields.io/badge/license-Apache--2.0-blue.svg)](https://github.com/LREN-CHUV/data-catalog-setup/blob/master/LICENSE)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/9adcf4cbd730472386d0e71ab27b9b6b)](https://www.codacy.com/app/mirco-nasuti/data-catalog-setup?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=LREN-CHUV/data-catalog-setup&amp;utm_campaign=Badge_Grade)
[![CircleCI](https://circleci.com/gh/LREN-CHUV/data-catalog-setup.svg?style=svg)](https://circleci.com/gh/LREN-CHUV/data-catalog-setup)

# Data Catalog Setup

## Introduction

The goal of this project is to provide a Docker container including Alembic and a Python model of the Data Catalog 
schema.

## Usage

Example: 
`docker run --rm -e "DB_URL=postgresql://postgres:postgres@localhost:5432/postgres" hbpmip/data-catalog-setup upgrade
head`

## Build

Run: `build.sh`

## Test

Run: `cd tests && ./test.sh`

## Push on Docker Hub

Run: `./docker_push.sh`
