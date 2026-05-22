# Bug Report

Title:
Browser back navigation causes inconsistent checkout state

Environment:
Chrome Browser
ChromeOS

Steps to reproduce:

1. Complete an order with several products
2. Return to catalog
3. Add new products to cart
4. Press browser Back button

Expected Result:
User returns to previous catalog state

Actual Result:
Application displays previous order confirmation page while current cart contains new products

Severity:
Medium
