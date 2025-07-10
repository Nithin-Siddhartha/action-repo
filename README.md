# GitHub Action Repo

This repo is used to test GitHub webhooks by triggering events like:

- Push
- Pull Request
- Merge

These events are captured by the Flask server in the [`webhook-repo`](https://github.com/Nithin-Siddhartha/webhook-repo) and logged in MongoDB.

### 🔍 Test Files

- `dev-test.txt`: Pull request test
- `merge_test.txt`: Merge test
- `test2.txt`: Push test
- `test3.txt`, `test4.txt`: Initial merge tests (treated as push)

This repo is part of a webhook integration demo.
