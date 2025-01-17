---
title: uPic tutorial - Amazon S3
date: 2019-07-30 20:33:43
toc: true
widgets:
  - type: toc
    position: right
sidebar:
  left:
    sticky: true
  right:
    sticky: true

---

<hr><!-- i18n --><div align="right">[**🇨🇳中文**](../) | **🇬🇧English**</div><!-- i18n -->

![Amazon S3 config](https://r2.svend.cc/tutorials/amazon_s3-host.png)

## 📝 Options instruction

- `Region`: The region of your Amazon S3,can be viewed in the Amazon S3 console panel.[Example](#🧰-Region-bucket-domain)
- `Bucket`: The bucket name of your Amazon S3,can be viewed in the Amazon S3 console panel.[Example](#🧰-Region-bucket-domain)
- `Access Key`: The Access Key of Amazon S3. [Example](#🔑-The-Secret-AccessKey-ID、Access-Key-Secret)
- `Secret Key`: The Secret Key of Amazon S3. [Example](#🔑-The-Secret-AccessKey-ID、Access-Key-Secret)
- `Domain`: Amazon S3 has default domain names. don't have to
- `Save Key`: The path to file storage (including folders). `Supports {year} {month} {day} {hour} {minute} {second} {since_second} {since_millisecond} {random} {filename} {.suffix} and etc. For example, the uploaded file is uPic.jpg, set to \"uPic/{filename}{.suffix}\", it will be saved as: uPic/uPic.jpg.`
- `The after Save Key input is Suffix`: For custom image processing. Amazon S3 is not currently supported, so reserve it first.

## 🧰 Region/bucket/domain

**View it by  open [Cloud storage](https://s3.console.aws.amazon.com/s3) console panel**

**⚠️ NOTICE: **

- 1.the bucket name should not be named in a format similar to: `blog.svend.cc`, such a bucket name S3 will be assigned a link of `https://s3.ap-northeast-2.amazonaws.com/blog .svend.cc/uPic.txt`, not a subdomain. Will cause the upload to fail. It should be named in a format similar to `blog-svend-cc`, and the links assigned by S3 will be generated as subdomains: `https://blog-svend-cc.s3.ap-northeast-2.amazonaws.com /uPic.txt`
- 2.when creating a bucket, don't check the permission settings to block all public access.

![Amazon S3 console](https://r2.svend.cc/tutorials/amazon_s3-info.png)

## 🔑 The Secret(AccessKey ID、Access Key Secret)

**get it by open console panel `My security credentials` -> `Access key (access key ID and secret access key)` **

- It is recommended to use Amazon's [IAM](https://docs.aws.amazon.com/zh_cn/IAM/latest/UserGuide/introduction.html) to create AccessKey ID and AccessKey Secret. Can better set key permissions, more secure

<hr>
