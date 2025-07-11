# action-repo

This repository contains a GitHub Actions workflow that sends a webhook event to a Flask server every time a `push` or `pull_request` occurs.

## 🔧 What This Repo Does

- Triggers a GitHub Action when you push or create a pull request
- Sends a `POST` request to your Flask server’s `/webhook` endpoint
- Payload includes event type, author, and target branch

---

## ⚙️ Workflow File Location

```bash
.github/workflows/webhook.yml
