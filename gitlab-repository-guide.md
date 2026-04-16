# How to Add a GitLab Repository to Vanta

## Prerequisites

- Admin or Owner access to your Vanta account
- Owner or Maintainer role in the GitLab repository you want to add
- A GitLab Personal Access Token (PAT) or GitLab group/project URL

---

## Steps

### 1. Open Vanta Integrations

1. Log in to your [Vanta dashboard](https://app.vanta.com).
2. In the left sidebar, click **Integrations**.
3. Search for **GitLab** and click on it.

### 2. Connect Your GitLab Account

You can connect via **OAuth** or a **Personal Access Token (PAT)**.

#### Option A — OAuth (recommended)

1. Click **Connect with GitLab**.
2. You will be redirected to GitLab. Authorize the Vanta application.
3. Once authorized, you'll be returned to Vanta.

#### Option B — Personal Access Token

1. In GitLab, go to **User Settings → Access Tokens**.
2. Create a new token with the following scopes:
   - `read_api`
   - `read_repository`
3. Copy the token.
4. In Vanta, paste the token into the **Personal Access Token** field and click **Connect**.

### 3. Select the Repository

1. After connecting, Vanta will list your available GitLab groups and projects.
2. Find the repository you want to monitor and toggle it **on**.
3. Click **Save** or **Confirm**.

### 4. Verify the Connection

1. Go to **Integrations → GitLab** in Vanta.
2. Confirm the repository appears under **Connected Repositories** with a green status.
3. Vanta will begin syncing data (this may take a few minutes).

---

## Troubleshooting

| Issue | Solution |
|-------|----------|
| Repository not appearing in the list | Ensure you have at least Maintainer role in GitLab |
| OAuth authorization fails | Check that your GitLab instance allows OAuth apps |
| PAT token rejected | Verify the token has `read_api` and `read_repository` scopes and hasn't expired |
| Sync shows errors | Check that Vanta's IP ranges are whitelisted if your GitLab instance uses IP allowlists |

---

## Notes

- Only repositories where you have **Maintainer** or **Owner** role can be connected.
- Self-hosted GitLab instances (GitLab CE/EE) may require additional network configuration to allow Vanta access.
- After connecting, Vanta monitors the repository for compliance checks such as branch protections, MR approvals, and secret scanning.
