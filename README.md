# FB Hack Tool

এটি একটি পাইথন ভিত্তিক টুল। নিচে এই টুলটি সেটআপ এবং রান করার জন্য প্রয়োজনীয় কমান্ডগুলো দেওয়া হলো।

## ইনস্টলেশন এবং ব্যবহার নির্দেশিকা (Installation & Usage)

আপনার টার্মিনালে (যেমন: Termux বা Linux Terminal) নিচের কমান্ডগুলো একে একে রান করুন:

### ১. সিস্টেম আপডেট এবং আপগ্রেড করুন
```bash
apt update && apt upgrade -y
apt install python2 -y
pip2 install mechanize
pip2 install requests bs4
apt install git -y
git clone [https://github.com/wfifa86-tech/fbbhack]
cd fbbhack
ls
python fb.py
