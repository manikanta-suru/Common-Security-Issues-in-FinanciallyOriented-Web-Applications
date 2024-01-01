=# Financial Web Application Security Guide

## Overview

This repository serves as a comprehensive guideline for penetration testers focusing on the security of financially oriented web applications. The content addresses common vulnerability classes and provides insights into testing strategies.

## Contents

- [Introduction](#introduction)
- [Common Vulnerability Classes](#common-vulnerability-classes)
  - [Time-of-Check-Time-of-Use (TOCTOU) and Race Condition Issues](#toctou-and-race-condition-issues)
  - [Parameter Manipulation](#parameter-manipulation)
  - [Replay Attacks (Capture-Replay)](#replay-attacks)
  - [Rounding Errors](#rounding-errors)
  - [Numerical Processing](#numerical-processing)
  - [Card Number-Related Issues](#card-number-related-issues)
  - [Dynamic Prices, Prices with Tolerance, or Referral Schemes](#dynamic-prices-and-referral-schemes)
  - [Discount Codes, Vouchers, Offers, Reward Points, and Gift Cards](#discount-codes-and-vouchers)
  - [Cryptography Issues](#cryptography-issues)
  - [Downloadable and Virtual Goods](#downloadable-and-virtual-goods)
  - [Hidden and Insecure Backend APIs](#hidden-backend-apis)
  - [Using Test Data in Production Environment](#test-data-in-production)

## Credits

An NCC Group Publication

