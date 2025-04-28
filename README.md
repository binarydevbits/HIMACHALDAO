# Himachal DAO Website

Static website for the Himachal Divisional Accounts Officers Association.

## Deployment with Vercel

### Option 1: Deploy with GitHub

1. Push this repository to GitHub
2. Log in to [Vercel](https://vercel.com)
3. Click "New Project"
4. Import your GitHub repository
5. Configure your project:
   - Framework Preset: Other
   - Root Directory: ./
   - Build Command: (leave empty for static site)
   - Output Directory: ./ (or specify if different)
6. Click "Deploy"

### Option 2: Deploy with Vercel CLI

1. Install Vercel CLI:
   ```
   npm install -g vercel
   ```

2. Log in to Vercel:
   ```
   vercel login
   ```

3. Deploy from project directory:
   ```
   vercel
   ```

4. Follow the interactive prompts to complete deployment

### Option 3: Manual Deployment

1. Log in to [Vercel](https://vercel.com)
2. Click "New Project"
3. Choose "Upload" option
4. Zip and upload this entire project directory
5. Configure settings as needed
6. Click "Deploy"

## Configuration

The site is configured for deployment using the `vercel.json` file, which sets up:
- Static site deployment 
- Proper routing for all static assets 