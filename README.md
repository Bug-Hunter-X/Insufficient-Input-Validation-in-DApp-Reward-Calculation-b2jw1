# Insufficient Input Validation in DApp Reward Calculation

This repository demonstrates a common error in decentralized applications (DApps): insufficient input validation.  The example shows a function `calculateReward` that is vulnerable to negative input values.  This can lead to errors, unexpected behavior, or even vulnerabilities in the application.

## Bug Description

The `calculateReward` function does not properly handle negative amounts.  This could result in exceptions or unintended calculations.

## Solution

The solution involves robust input validation.  The improved version handles negative amounts gracefully, either by rejecting the transaction or returning a default value.