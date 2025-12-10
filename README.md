# WinBid - E-Bidding System Prototype

## Overview
WinBid is an E-bidding system designed to address the **seller overstock problem** by providing a centralized, standard platform to gather buyers. This allows sellers to liquidate their inventory more efficiently through competitive bidding sessions.

## Problem Statement
Sellers often face challenges with overstocked items that take up space and tie up capital. finding interested buyers quickly for these specific items can be difficult through traditional fixed-price channels.

## Solution
WinBid offers a dynamic marketplace where:
*   **Sellers** can easily list overstocked items for auction, reaching a concentrated pool of interested buyers.
*   **Buyers** can discover deals and bid on items in real-time.
This efficiency helps sellers clear stock faster and buyers find great value.

## Prototype Features

### 1. Authentication Flow (`login/`)
*   **Role-Based Access**: Toggle between **Buyer** and **Seller** login.
*   **Mock Functionality**:
    *   **Buyer Login**: `buyer@gmail.com` / `123456`
    *   **Seller Login**: `seller@gmail.com` / `123456`
*   **Standard Features**: Sign Up, Forgot Password (OTP Flow), Reset Password.
*   **Design**: Clean, colorless (monochrome) UI with clear role indicators.

### 2. Seller Interface (`seller/`)
*   **Dashboard**: Overview of 'Active' and 'Ended' bidding sessions.
*   **Inventory Management**:
    *   **Add Product**: Detailed form to list new items with images and pricing.
    *   **View/Edit Product**: Manage product details.
*   **Session Management**:
    *   **Session Details**: Monitor live statistics (Current Bid, Time Left).
    *   **Empty State**: Handle sessions with no bids.
*   **Order Fulfillment**: Track orders (Pending, Shipped, Cancelled, Returns).

### 3. Buyer Interface (`buyer/`)
*   **Home Stream**: Browse active bidding sessions.
*   **Bidding**: Real-time interaction to place bids on items.
*   **Profile**: Manage personal details and settings.
*   **Wallet/Payment**: Integrated payment flow simulations.

## Usage
To explore the prototype:
1.  Open `login/index.html` in your browser.
2.  Select your role (Buyer or Seller).
3.  Use the mock credentials provided above to sign in.
4.  Navigate through the respective dashboards.

## Technology
*   **Frontend**: HTML5, CSS3 (Custom Monochrome Theme), Vanilla JavaScript.
*   **Design System**: Minimalist, clean UI focusing on usability and content.
