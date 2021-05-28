# BECEF-NETWORK
## git CLI manual 
### টুল কনফিগার
#### লোকাল রিপোজিটরির জন্য টুল কনফিগার করা
###### নাম ঠিক করুন যেটা আপনি কমিট ট্রান্সেকশনের সাথে সংযুক্ত করতে চান।
```
$ git config --global user.name "[name]"
```
###### ইমেইল ঠিক করুন 
```
$ git config --global user.email "[email address]"
```

### রিপোজিটরি তৈরি
#### নতুন রিপোসিটোরি শুরু অথবা একটি বিদ্যমান URL থেকে শুরু করুন।
###### নির্দিষ্ট নাম দিয়ে একটি নতুন রিপোসিটোরি তৈরি করুন।
```
$ git init [project-name]
```
###### একটি repository এবং তার সম্পূর্ণ সংস্করণ ইতিহাস ডাউনলোড করুন।
```
$ git clone [url]
``` 
### পরিবর্তন করা
#### সম্পাদনা পর্যালোচনা করুন এবং একটি কমিট ট্রান্সেকসন ক্রাফট করুন।
###### সকল ফাইল লিস্ট করুন যা কমিট করা হবে।
```
$ git status
```
###### ফাইলগুলোর পার্থক্য দেখুন যেগুলো এখনো staged হয়নি।
```
$ git diff
```
###### সংস্করনের জন্য প্রস্তুতি ফাইল স্ন্যাপশট করুন।
```
$ git add [file]
```

