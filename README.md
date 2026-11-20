# mpwa-api-webhook-example

This is an example **Webhook** and **REST API** implementation in PHP for building chatbots and automated integrations with **MPWA (Multi-Device WhatsApp Gateway)**. It demonstrates how to send outbound messages via API and receive/respond to incoming WhatsApp messages using a structured webhook setup.

## 📁 Repository Structure

- **`ApiExample/`**  
  Contains service classes and usage examples for sending outbound WhatsApp messages via REST API (`ApiUsageExample.php`, `MpwaService.php`, and `SimpleCurl.php`).
- **`SimpleExampleWebhook/`**  
  A lightweight, single-file webhook receiver example for handling and replying to incoming messages directly.
- **`WebhookExample/`**  
  A structured webhook implementation separating configuration and message handlers for various incoming message types (text, media, location, and bot commands).

## 🚀 Getting Started

### 1. Clone the Repository
Clone this repository to your local machine or web server:
```bash
git clone [https://github.com/toryhonda/mpwa-api-webhook-example.git](https://github.com/toryhonda/mpwa-api-webhook-example.git)
cd mpwa-api-webhook-example
