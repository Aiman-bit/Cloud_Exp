☁️ AWS Cloud Resume Challenge (My Beginner Journey 🚀) (Will be continued after AWS CCP Exam)

www.aiman.test-resume.com

Hey there! This is my personal challenge to get my hands dirty (and brain sweaty) with AWS. I wanted to build something real, not just watch tutorial after tutorial. So I turned my resume into a full-stack AWS-powered project.

🔧 What’s Inside
☁️ Hosting with S3 + CloudFront + Route 53
  - Static frontend deployed to S3
  - Distributed globally using CloudFront
  - HTTPS enabled with default cert 
  - CDN + Custom Domain via Route 53

🛠️ Infrastructure as Code with Terraform
  - Provisioned the S3 bucket
  - Spun up a CloudFront distribution
  - Managed policies for public access and bucket behavior

📡 API Gateway + Lambda + DynamoDB
  - Built a backend API for visitor tracking
  - Used Lambda to run the logic
  - Count data stored in DynamoDB
  - Added IP hash check so reloading 100 times = not 100 visitors 😂

💡 Why I Did This
I just wanted something to prove I can build stuff with AWS — no fluff. This is still a work in progress, but already it's taught me more than any Udemy course alone could.
And trust me, I’m not stopping here (I hope). 

🧠 What I Actually Did

  🔨 Built the frontend using React + Vite
  🔗 Hooked it up with API Gateway and a custom Lambda function
  🔐 Created a local hashing logic using IP + User-Agent (stored in browser)
  🧠 Prevented inflated visitor counts (no fake refresh farming allowed!)
  🧬 Connected all the dots: Lambda ↔ DynamoDB ↔ React
  📊 Stored data in DynamoDB using visitorId and visits
  🌐 Mapped a custom domain using Route 53 and linked it to CloudFront
  🛡️ Handled IAM permissions, CORS config, and tested with Postman
  🔒 Secured my custom domain with HTTPS using AWS Certificate Manager (ACM)


🔭 What’s Next?
Here’s what I plan to explore soon:
  📈 Add a simple dashboard (maybe with CloudWatch Logs/Insights)
  📬 Integrate a contact form using SES + Lambda
  🧪 Try deploying the entire stack using only Terraform
  💻 Add GitHub Actions for auto-deploy (CI/CD flex)

🧵 TL;DR
It might look simple, but every piece here was a new skill unlocked for me — especially tying frontend, backend, and cloud infra together. If you're reading this and just getting started with AWS too, I feel you :)

Let’s keep building. 💪


