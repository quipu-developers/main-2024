# QUIPU Main Web 2024

서울시립대학교 컴퓨터 학술 중앙동아리 QUIPU의 2024년 메인 웹사이트 프로젝트입니다.  
동아리 소개, 회원 모집, 활동 및 프로젝트 기록 기능을 제공합니다.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Development Timeline](#development-timeline)
- [Getting Started](#getting-started)

## Overview

본 프로젝트는 QUIPU의 공식 메인 웹사이트로, 대외 안내와 활동 아카이브 제공을 목표로 개발되었습니다.  
프론트엔드와 백엔드를 분리한 구조로 운영되며, 사용자에게 모집 정보와 연도별 활동 정보를 제공합니다.  
또한 2024년 하반기 이벤트 운영을 위해 별도 룰렛 기능을 포함했습니다.

## Features

- 동아리 소개 및 신규 회원 모집 안내
- 연도별 동아리 활동 기록 제공
- 웹 개발 프로젝트 쇼케이스 제공
- 랜덤 선물 뽑기 룰렛 이벤트 기능 제공

룰렛 이벤트 관련 소스는 [roulette-event branch](https://github.com/quipu-developers/main-2024/tree/roulette-event)에서 확인할 수 있습니다.

## Tech Stack

- Frontend: React
- Backend: Express
- Database: MySQL

## Development Timeline

| Project | Period |
|---|---|
| Main Web | 2024.01 - 2024.03 |
| Roulette Event | 2024.08 |

## Getting Started

### Install

```bash
cd frontend && npm install
cd ../backend && npm install
```

### Run

```bash
# backend
cd backend
npm start

# frontend
cd ../frontend
npm start
```
