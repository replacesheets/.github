# COD Manager

> A comprehensive solution for ecommerce store owners to streamline order confirmation and fulfillment processes.

## 🎯 Project Overview

This project aims to revolutionize ecommerce operations by automating order confirmation and saisie processes, delivering faster, more cost-effective, and higher-quality confirmation and delivery rates for store owners.

---

## 🚀 Deployment Environments

### Production
- **Frontend:** [https://cod-manager.com/](https://cod-manager.com/)
- **Backend:** [https://api.cod-manager.com/](https://api.cod-manager.com/)
- **Database:** MongoDB Atlas (production)

### Staging
- **Frontend:** [https://ecomircili.onrender.com](https://ecomircili.onrender.com)
- **Backend:** [https://staging.api.cod-manager.com/](https://staging.api.cod-manager.com/)
- **Database:** MongoDB Atlas (staging)

### Development
- **Database:** MongoDB (local dev environment)

---

## 📦 Deploying a New Branch on Octenium

Follow these steps to deploy a new branch:

1. Create a new subdomain
2. SSH into the subdomain folder
3. Initialize Git and connect to remote:
   ```bash
   git init
   git remote add origin <ssh_url>
   git pull origin <remote_branch_name>
   ```
4. Add environment variables:
   ```bash
   # Create .env file with required variables
   ```
5. Create the Node.js app
6. Install dependencies:
   ```bash
   npm install
   ```
7. Start the application

---

## 🌿 Git Workflow

### Branch Structure
- **Production:** `main`
- **Staging:** `staging`
- **Development:** `dev`

### Development Workflow

1. **Develop** - Create a feature branch and implement changes
2. **Merge to Dev** - Merge your feature branch to `dev`
3. **Test Locally** - Verify changes in local environment
4. **Merge to Staging** - Merge `dev` to `staging`
5. **Push to Remote** - Push to `origin/staging` (both frontend and backend)
6. **Test Staging** - Verify changes in staging environment
7. **Create PR** - Open Pull Request to `main` for frontend and backend
8. **Review Changes** - Review the PR thoroughly
9. **Accept PR** - Merge to production
10. **Done!** ✅

---

## 🔐 Generating Encryption Keys

Use the following command to generate secure encryption keys:

```bash
node -e "console.log(require('crypto').randomBytes(32).toString('hex'))"
```

---

## 📝 Notes

- Always test changes in local and staging environments before deploying to production
- Ensure `.env` files are properly configured for each environment
- Keep encryption keys secure and never commit them to version control

---

* may this project bring success and prosperity!* 🤲
