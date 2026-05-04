# FREE Deployment Guide (No Credit Card Required)

Follow these steps to host your **EDUProfile** system for free on Vercel.

## 1. Prepare your GitHub Repository
1. Ensure your code is uploaded to [https://github.com/itsmeRampage/EduTools](https://github.com/itsmeRampage/EduTools).
2. Make sure the repository is **Public**.

## 2. Deploy to Vercel (Free)
1. Go to [Vercel](https://vercel.com/signup) and sign up using your **GitHub** account.
2. Click **"Add New..."** and then **"Project"**.
3. Find your `EduTools` repository in the list and click **"Import"**.
4. **Environment Variables (CRITICAL)**:
   - Expand the **"Environment Variables"** section.
   - Add these 4 keys from your `src/firebase/config.ts`:
     - `NEXT_PUBLIC_FIREBASE_API_KEY`
     - `NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN`
     - `NEXT_PUBLIC_FIREBASE_PROJECT_ID`: `studio-4144227073-47fa3`
     - `NEXT_PUBLIC_FIREBASE_APP_ID`
5. Click **"Deploy"**.

## 3. Your Website is Live!
- Vercel will give you a link like `edutools.vercel.app`.
- Send this link to your professors. It is permanent and free.

## 4. Troubleshooting Student Access
- If a student cannot log in, they should go to `/student-portal/forgot-password`.
- They enter their **Student ID** and click Reset.
- Their password is now their **Student ID**. They can then log in and change it to a private password.
