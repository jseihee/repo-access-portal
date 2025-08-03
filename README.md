# 🚪 Private Repo Access Portal

[![Invite on Access Request](https://github.com/jseihee/repo-access-portal/actions/workflows/invite-on-request.yml/badge.svg)](https://github.com/jseihee/repo-access-portal/actions/workflows/invite-on-request.yml)

A simple GitHub Access Portal that automates invitations to the private repository. <br>
Users open a formatted issue to request access, and a GitHub Action sends the invite and closes the request.

---

## 📝 Usage (for Requesters)

1. **Navigate to this repository** at `https://github.com/jseihee/repo-access-portal`.
2. Click **Issues → New issue**.
3. Select the **Access Request** template.
4. Enter your **GitHub username** in the form and submit.
5. A maintainer will review your request. If approved, you’ll receive an invite to the private repository.

---

## 📁 Repository Structure

```
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── access_request.yml     # Form template for users to request access
│   └── workflows/
│       └── invite-on-request.yml  # Automation to send invites
└── README.md                      # This file
```

