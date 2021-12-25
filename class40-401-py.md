# Dynamic Routes

steps:
- First, we’ll create a page called [id].js under pages/posts. Pages that begin with [ and end with ] are dynamic routes in Next.js.
- In pages/posts/[id].js, we’ll write code that will render a post page — just like other pages we’ve created.
- import Layout from '../../components/layout'
export default function Post() {
  return <Layout>...</Layout>
}
- We’ll export an async function called getStaticPaths from this page. In this function, we need to return a list of possible values for id

## Render Markdown
- To render markdown content, we’ll use the remark library. First, let’s install it:
> npm install remark remark-html

# Deploying NextJS App
- git remote add origin https://github.com/<username>/nextjs-blog.git
- git push -u origin main
- Deploy to Vercel
- Import your nextjs-blog repository

vercel features:
1. Custom Domains: Once deployed on Vercel, you can assign a custom domain to your Next.js app.
2. Environment Variables: You can also set environment variables on Vercel. 
3. Automatic HTTPS: HTTPS is enabled by default (including custom domains) and doesn't require extra configuration. We auto-renew SSL certificates.
  


  

