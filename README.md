# 🚀 Flask Web App Development Tutorials by Hammad Zahid

Welcome to the **Flask Web App Development Series** repository.  
This project contains complete tutorials, deployment guides, and practical examples for building and deploying Flask web applications using Python and cloud platforms like AWS EC2.

Created and maintained by **Hammad Zahid** — AI Engineer, Data Scientist, and Python Developer.

---

# 📌 About This Repository

This repository includes:

- 🌐 Flask web application tutorials
- 📊 Data science and EDA web apps
- ☁️ AWS EC2 deployment guide
- 🔐 Security & production deployment tips
- ⚡ Background process management
- 🐍 Python virtual environment setup
- 🚀 Beginner-to-advanced Flask workflows

---

# 👨‍💻 Author

## Hammad Zahid
- 🎓 Student at Virtual University of Pakistan
- 🤖 AI & Data Science Enthusiast
- 📈 Data Analyst & Visualization Developer
- 🐍 Python Programmer

---

# 🔗 Connect With Me

- 💼 LinkedIn: https://linkedin.com/in/hammadzahid
- 🐙 GitHub: https://github.com/hammadzahid
- 📺 YouTube: https://youtube.com/@hammadzahid
- 🌐 Portfolio: https://hammadzahid.vercel.app

---

# 📂 Project Repository

GitHub Repository:

```bash
https://github.com/AammarTufail/flask_webapp_development_series.git
```

---

# 🎥 Flask Tutorial Playlist

Watch the complete Flask tutorial playlist on YouTube to learn:

- Flask fundamentals
- Web app deployment
- APIs
- Templates
- Forms
- Database integration
- Production hosting

---

# ☁️ Deploy Flask Web App on AWS EC2

A complete step-by-step deployment guide for beginners.

---

# 🛠 Step 1 — Create AWS Account

1. Visit AWS:
   ```bash
   https://aws.amazon.com/
   ```

2. Create your AWS account.

3. Sign in to the AWS Management Console.

---

# 🚀 Step 2 — Launch EC2 Instance

Open EC2 Dashboard:

```bash
https://console.aws.amazon.com/ec2/
```

### Configure Instance

| Setting | Recommended Option |
|---|---|
| AMI | Ubuntu Server 20.04 LTS |
| Instance Type | t2.micro |
| Storage | Default |
| Tags | Optional |

---

# 🔐 Step 3 — Create Key Pair

- Create a new `.pem` key pair
- Download and save securely
- Never share your private key publicly

Example:

```bash
my-aws-key.pem
```

---

# 🌍 Step 4 — Configure Security Group

Allow these ports:

| Service | Port |
|---|---|
| SSH | 22 |
| HTTP | 80 |
| HTTPS | 443 |
| Flask / Streamlit | 8501 |

### Important:
Enable access from:

```bash
Anywhere (0.0.0.0/0)
```

---

# 🔌 Step 5 — Connect to EC2 Instance

### Change key permissions

```bash
chmod 400 your-key-pair.pem
```

### Connect using SSH

```bash
ssh -i "your-key-pair.pem" ubuntu@your-instance-public-ip
```

---

# 📦 Step 6 — Install Required Software

Update Ubuntu packages:

```bash
sudo apt update && sudo apt upgrade -y
```

Install Python and Git:

```bash
sudo apt install python3-pip python3-venv git -y
```

---

# 📥 Step 7 — Clone GitHub Repository

```bash
git clone repository-url
```

Move into project directory:

```bash
cd project-folder
```

---

# 🐍 Step 8 — Create Virtual Environment

Create environment:

```bash
python3 -m venv env
```

Activate environment:

```bash
source env/bin/activate
```

---

# 📚 Step 9 — Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶️ Step 10 — Run Flask App

```bash
python3 app.py
```

---

# 🌐 Step 11 — Access Web App

Open browser:

```bash
http://your-instance-public-ip:8501
```

---

# ⚡ Run Flask App in Background

```bash
nohup python3 app.py &
```

---

# 🛑 Stop Running Flask App

Find process:

```bash
ps -aux | grep app.py
```

Kill process:

```bash
kill -9 process-id
```

---

# 🖥 GUI Access Using WinSCP & PuTTY

## Recommended Tools

| Tool | Purpose |
|---|---|
| PuTTY | SSH Terminal |
| WinSCP | File Transfer |

### Benefits

- Easy file upload/download
- GUI-based server access
- Terminal management

---

# 🌍 Use Custom Domain Name

Instead of IP:

```bash
http://your-domain.com
```

You can use:

- AWS Route 53
- GoDaddy
- Namecheap
- Cloudflare

Point your domain to EC2 public IP.

---

# 🔒 Security Best Practices

## Always:

- Use HTTPS
- Install SSL certificates
- Enable firewall
- Keep packages updated
- Use strong SSH keys
- Disable root login
- Create backups regularly

---

# 📊 Monitor Your Server

Recommended monitoring:

- AWS CloudWatch
- UptimeRobot
- Netdata

Monitor:

- CPU usage
- RAM usage
- Traffic
- Downtime

---

# 💾 Backup Recommendations

Always back up:

- Database
- Uploaded files
- Environment variables
- Source code

Use:

- AWS Snapshots
- GitHub
- External storage

---

# 💰 Save AWS Costs

Terminate unused instances.

## Steps:

1. Open EC2 Dashboard
2. Select running instance
3. Click:

```bash
Actions → Instance State → Terminate
```

⚠️ Warning:

Terminating instance deletes all data permanently.

---

# 📚 Technologies Used

- Python
- Flask
- HTML/CSS
- Bootstrap
- AWS EC2
- Git & GitHub
- Linux Ubuntu

---

# ⭐ Features

✅ Beginner Friendly  
✅ Cloud Deployment  
✅ Production Ready  
✅ Lightweight Setup  
✅ AWS Hosting Guide  
✅ Flask Best Practices  
✅ Background Execution  
✅ Domain Configuration  

---

# 🤝 Contributing

Contributions are welcome.

1. Fork repository
2. Create feature branch
3. Commit changes
4. Push code
5. Open pull request

---

# 📜 License

This project is licensed under the MIT License.

---

# ❤️ Support

If you found this project helpful:

- ⭐ Star the repository
- 🍴 Fork the project
- 📢 Share with others

---

# 🙌 Acknowledgements

Special thanks to:

- Flask Community
- AWS
- Open Source Contributors
- Python Developers Community

---

# 📬 Contact

## Hammad Zahid

📧 Email: hammadzahid.dev@gmail.com  
💼 LinkedIn: https://linkedin.com/in/hammadzahid  
🐙 GitHub: https://github.com/hammadzahid  

---

# 🚀 Happy Coding!

Build. Learn. Deploy. Scale.

Made with ❤️ by **Hammad Zahid**
