**🎉 Project Overview**
Vercel Chat SDK deverceled and deployed on Cloudflare Workers. 

............

**📍 Live**
Link to the live version: https://chatgoat.dreemrworld.workers.dev

............

**💾 Installation**
Download the project to your computer and install needed packages with command:

$ git clone https://github.com/dreemrworld/chat-sdk-on-cloudflare
cd chat-sdk-on-cloudflare

$ pnpm install

$ pnpm dev 

$ pnpm deploy


Thats it!

............

**🔧 Tech/framework used**

**Front-end**
TypeScript,Tailwind CSS, HTML 

**Back-end**
Cloudflare workers 

............

**Cloudflare workers** offers a very generous free plan on everything you need

**AI Gateway** - replaces OpenAI SDK 

**D1** - replaces Neon 

**R2** - replaces Blob

**KV** - replaces Resend 

............

**Why this stack?**

The **HTML, Tailwind, TypeScript \+ Workers** stack is technically superior for building high-performance, low-cost webapps because it is perfectly engineered for cloudflare's V8 edge javascript engine that also powers your favorite chromium web browser. I call it KISS (keep it super simple) edge stack because 99% of web projects do not require complex frameworks. In fact they only add unnecessary abstraction layers, higher latency, bloat, dependency hell and security vulnerabities. In the end your browser will display any framework as a html, css and javascript website that can be downloaded,edited and used offline by anyone. 

This project is deployed as less than **1mb**. Cloudflare workers has a 3mb limit. If you ever tried to deploy a nextjs project on cloudflare with an adapter then you have certainly crossed this limit before. With KISS edge stack you will never worry about the 3mb limit again. 

If you use cloudflare workers backend then all you'd need in theory is to add a few lines of code and bind into wrangler.jsonc. Locally your node_modules will be around 300mb and it will be only cloudflare's dependencies. You will not need to install any other dependency to deploy a fully functional enterprise grade globally disributed on the edge webapp.  

**Evidence:**

* **Zero Frontend Dependencies:** No framework runtime. Pure HTML, CSS, and JS mean instant load, no bundle bloat, and no client-side performance tax.

* **Minimal, Native Backend:** Cloudflare Workers and Durable Objects are serverless primitives. No VMs, containers, or complex orchestration. Code runs in microsecond-start V8 isolates.

* **Unmatched Cost Efficiency:** You pay only for CPU time (microseconds), not idle time (seconds/minutes). This is orders of magnitude cheaper than Vercel,AWS/Azure for I/O-heavy tasks.

* **Global Low Latency:** The entire stack (CDN for assets, Workers for logic) runs on Cloudflare's 300+ global edge locations, ensuring the fastest possible response for every user.

* **Free Tier Leverage:** This architecture consumes minimal resources, allowing even complex-seeming apps to operate entirely within the generous free usage limits.

This stack wins on pure technical merit: simplicity, speed, cost, and global scale are built into its foundation

............

**Limitations**
Right now this is only a front-end and may still have legacy code. Sharing with the FOSS community so we can improve together. 

............

If you encounter a problem, write to this e-mail address: carlos@goat.africa . 

............

May the yield be with you. Don't forget to leave a star!
 

