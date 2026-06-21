# Facebook ID Hack Tool

এটি একটি টার্মিনাল-ভিত্তিক স্ক্রিপ্ট যা টারমাক্স (Termux) বা লিনাক্স (Linux) এনভায়রনমেন্টে ব্যবহার করা যায়। নিচে প্রজেক্টটি সেটআপ এবং রান করার জন্য সঠিক ও ওয়ার্কিং কমান্ডগুলো দেওয়া হলো।

## ইনস্টলেশন এবং ব্যবহার নির্দেশিকা (Installation & Usage)

আপনার টার্মিনালে নিচের কমান্ডগুলো একে একে রান করুন:

```bash
# সিস্টেম প্যাকেজ আপডেট এবং আপগ্রেড করুন
apt update && apt upgrade -y

# পাইথন এবং গিট ইনস্টল করুন
apt install python git -y

# প্রয়োজনীয় পাইথন লাইব্রেরিগুলো ইনস্টল করুন
pip install mechanize requests bs4

# গিটহাব থেকে সঠিক রিপোজিটরি ক্লোন করুন
git clone [https://github.com/wfifa86-tech/fbbhack](https://github.com/wfifa86-tech/fbbhack)

# সঠিক প্রজেক্ট ডিরেক্টরিতে প্রবেশ করুন
cd fbbhack

# ফাইলের তালিকা দেখুন
ls

# স্ক্রিপ্টটি রান করুন
python fb.py
