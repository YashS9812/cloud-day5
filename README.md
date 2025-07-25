# ☁️ AWS Cloud — Day 5: IAM Custom Policy for S3 (CLI Practice)

## 🔐 What I Did
- Created a custom IAM policy (`AllowS3ListOnly`) allowing only `s3:ListAllMyBuckets`
- Attached policy to an IAM user
- Configured AWS CLI using the user’s access keys
- Verified bucket listing via `aws s3 ls`
- Ensured user could **only list**, not create/delete buckets

## 🧠 What I Learned
- How fine-grained IAM permissions work
- Importance of least privilege principle
- Practical use of custom policies for secure access

## 🧹 Cleanup
- IAM user deleted after testing
- EC2 instance and volumes verified stopped/deleted to avoid billing
- S3 buckets managed to stay within free tier

## 📸 Screenshot
- CLI output of listing S3 buckets using a user with limited access

