# ISO-27001-2022-Compliance-Gap-Assessment

তোমার Manager বললেন:

"আমাদের Software Engineering Department-এর ISO 27001:2022 Compliance Gap Assessment করতে হবে।"

তুমি সরাসরি Word Document খুলে লেখা শুরু করবে না।

প্রথমে ৫টি কাজ করবে।
Real-life GRC Workflow
1. Understand the Business
   
   কোম্পানি কী করে, কোন Services দেয় এবং কীভাবে Revenue তৈরি করে?
   
3. Identify Stakeholders
   
   কোন Department-এর কাছ থেকে তথ্য নিতে হবে?
   
5. Collect Information
   
   Interview, Questionnaire, Existing Documents ও Evidence সংগ্রহ করবে।
   
7. Define Assessment Boundary
   
   কোন Location, Department, Process, System ও Information মূল্যায়ন করবে?
   
9. Prepare Scope Document
   
   সংগৃহীত তথ্যের ভিত্তিতে Scope Draft তৈরি করে Review ও Approval নেবে।

   ২. তোমার Scope Document-এর প্রতিটি Section কীভাবে লিখবে?
   
Section 1: Organization
প্রশ্ন: কোম্পানি সম্পর্কে কী জানবে?

Real Life-এ যেসব তথ্য সংগ্রহ করবে:
- Company Name
- Business Activities
- Industry
- Headquarters
- Business Locations
- Organizational Structure
- Products and Services
  
তথ্য কোথা থেকে নেবে?
Source	কী জানতে পারবে
Official Website	Business Activities
HR Department	Employee Structure
Management	Business Objectives
Operations Team	Business Processes
IT Department	Technology Environment

Section 2: Assessment Objective

প্রশ্ন: আমরা কেন Assessment করছি?

Objective লেখার আগে Manager বা Management-এর কাছ থেকে Assessment-এর Purpose বুঝবে।

উদাহরণ:
- ISO 27001 Compliance Gap শনাক্ত করা।
- Security Control-এর দুর্বলতা খুঁজে বের করা।
- Risk Management উন্নত করা।
- Audit Readiness মূল্যায়ন করা।

ISO 27001-এর নিয়ম অনুযায়ী, অফিসের সব কর্মীর কম্পিউটারে শক্তিশালী পাসওয়ার্ড এবং টু-ফ্যাক্টর অথেনটিকেশন (2FA) থাকতে হবে। কিন্তু চেক করে দেখা গেল, অর্ধেক কর্মী খুব সাধারণ পাসওয়ার্ড ব্যবহার করেন এবং 2FA চালু নেই। এই যে নিয়মের সাথে বাস্তবের অমিল বা ঘাটতি খুঁজে বের করা হলো—এটিই হলো ISO 27001 Compliance Gap শনাক্ত করা।

কেন এটি করা হয়?
মূল অডিট বা সার্টিফিকেশন পরীক্ষার আগে নিজেদের দুর্বলতাগুলো খুঁজে বের করে তা ঠিক করার জন্য এটি করা হয়, যাতে কোম্পানি সহজেই ISO 27001 সার্টিফিকেট অর্জন করতে পারে।


Section 3: Assessment Scope
এটি সবচেয়ে গুরুত্বপূর্ণ Section।

এখানে চারটি বিষয় মাথায় রাখবে:
1. কোন Department?
2. কোন Business Process?
3. কোন Location?
4. কোন Information System?
উদাহরণ:
Scope Element	Example
Department	Software Engineering
Process	Software Development Lifecycle
Location	Bangladesh Office
System	Development & Deployment Systems

বাস্তবে এগুলো অনুমান করে লিখবে না। Department Head, IT Manager এবং Process Owner-এর সঙ্গে আলোচনা করে Confirm করবে।

Section 4: In-Scope Activities

প্রশ্ন: কোন কোন কাজ আমরা পরীক্ষা করব?

এখানে Department-এর কাজগুলো Process অনুযায়ী লিখবে।

ধরো Software Engineering Department-এর কাজ:
- Software Development
- Code Review
- Application Testing
- Deployment
- Change Management
- 
এখন প্রতিটি কাজের জন্য Process Owner-এর কাছে জানতে চাইবে:
- কাজটি কীভাবে সম্পন্ন হয়?
- কে অনুমোদন দেয়?
- কোন Policy অনুসরণ করা হয়?
- কী Security Control আছে?
- কী Evidence পাওয়া যাবে?
  
উদাহরণ:
Activity	কী যাচাই করবে	সম্ভাব্য Evidence
Code Review	Code Review বাধ্যতামূলক কি না	Pull Request Records
Access Management	কে Repository Access পায়	Access List
Deployment	কে Production Deployment অনুমোদন করে	Deployment Approval
Backup	Database Backup হয় কি না	Backup Logs

এখানে একটা গুরুত্বপূর্ণ বিষয়: Activity-এর নাম লিখলেই হবে না। কীভাবে কাজটি হয় এবং কী Evidence দিয়ে যাচাই করবে সেটাও বুঝতে হবে।


Section 5: In-Scope Information Assets

প্রশ্ন: কোম্পানির কোন Information Assets সুরক্ষিত রাখতে হবে?

প্রথমে Asset Owner-দের কাছ থেকে Asset Inventory সংগ্রহ করবে।

উদাহরণ:
Asset	Owner	Classification
Source Code	Development Team	Confidential
Database	Database Administrator	Confidential
AWS Credentials	DevOps Team	Restricted
Project Documents	Project Manager	Internal
Security Logs	Security Team	Confidential

এখানে Classification নিজে ইচ্ছামতো দেবে না।

কোম্পানির Data Classification Policy থাকলে সেটি অনুসরণ করবে। না থাকলে প্রস্তাবিত Classification তৈরি করে Asset Owner ও Management-এর অনুমোদন নেবে।

Section 6: Relevant Personnel

প্রশ্ন: কার কাছ থেকে তথ্য সংগ্রহ করবে?

যাদের কাজ Assessment-এর সঙ্গে সম্পর্কিত, তাদের Stakeholder হিসেবে চিহ্নিত করবে।

Stakeholder	কেন প্রয়োজন?

CTO / IT Manager	Technology Governance
Development Manager	Development Process
DevOps Lead	Cloud & Deployment
QA Lead	Testing & Quality
HR Manager	Employee Lifecycle
Information Security Officer	Security Controls
Project Manager	Client & Project Requirements

এখানে প্রতিটি ব্যক্তির কাছ থেকে কী তথ্য বা Evidence চাইবে সেটাও নির্ধারণ করবে।

সময় বাঁচানো: আগে থেকেই ঠিক করা থাকলে যে কার কাছ থেকে কী লাগবে, অ্যাসেসমেন্টের সময় অপ্রয়োজনীয় মিটিং বা ভুল মানুষের কাছে যাওয়ার ঝামেলা কমে যায়।

ধাপ ৩: তথ্য সংগ্রহের মাধ্যম ঠিক করা
সব তথ্য একভাবে নেওয়া যায় না। তাই ৩টি পদ্ধতি ব্যবহার করুন:

ইন্টারভিউ (Interview): তাদের সাথে ৩০-৪৫ মিনিটের মিটিং করে জিজ্ঞেস করুন তারা কাজগুলো কীভাবে করেন।

ডকুমেন্ট রিভিউ (Document Review): তাদের তৈরি করা পলিসি, এসওপি (SOP) বা চেকলিস্টগুলো চেয়ে নিন।

সরাসরি পর্যবেক্ষণ (Observation/Walkthrough): স্ক্রিন শেয়ারের মাধ্যমে সরাসরি সিস্টেমে ঢুকে দেখুন (যেমন: আসলেই টু-ফ্যাক্টর অথেনটিকেশন বা ব্যাকআপ চালু আছে কি না)।

ধাপ ৪: একটি 'Evidence Tracker' তৈরি করা
একটি এক্সেল শিটে (Excel Sheet) লিখে রাখুন—কার কাছে কী চাওয়া হয়েছে, কবে চাওয়া হয়েছে, এবং সেগুলো জমা দেওয়া হয়েছে কি না (Status: Pending / Received / Verified)।


Section 7: Out-of-Scope Activities
প্রশ্ন: কোন বিষয়গুলো এই Assessment-এর বাইরে থাকবে এবং কেন?

এটি খুব সতর্কতার সঙ্গে করতে হয়।

উদাহরণ:
Activity	কেন বাদ
HR Operations	নির্বাচিত Development Assessment-এর বাইরে
Finance Operations	নির্বাচিত Assessment Boundary-এর বাইরে
BPO Operations	আলাদা Business Process

কিন্তু মনে রাখবে, কোনো Department-কে বাদ দিলেই তার সঙ্গে সম্পর্কিত সব Risk বাদ হয়ে যায় না।

উদাহরণ: HR Department আমাদের Assessment-এর বাইরে হলেও Developer-দের Joining, Transfer ও Resignation-এর সময় Access Provisioning/Revocation পরীক্ষা করা প্রয়োজন হতে পারে।

এটিই GRC Analyst-এর Critical Thinking।

Non-Compliant (অমান্য করা): এর মানে হলো আপনি নিশ্চিতভাবে প্রমাণ পেয়েছেন যে কোম্পানি নিয়মটি মানছে না (যেমন: তাদের কোনো পাসওয়ার্ড পলিসিই নেই)।

Not Available (তথ্য পাওয়া যায়নি): এর মানে হলো কোম্পানি হয়তো নিয়মটি মানছে, কিন্তু আপনাকে এখনো সেই ডকুমেন্ট বা প্রমাণ দেয়নি।


আপনি প্রমাণ না দেখেই যদি কাউকে Non-Compliant বলে দোষী সাব্যস্ত করেন, তবে অডিটের ভাষায় সেটি একটি বড় ভুল বা মিথ্যা অভিযোগ হবে। তাই যেটি দেখা সম্ভব হয়নি, সেটিকে সোজাসাপ্টা Not Available বা Not Verified লিখতে হয়।

২. এটি করে কী লাভ? (Benefits)
১. নিজের পেশাগত সুরক্ষা (Professional Protection): ভবিষ্যতে যদি কোনো বড় অডিটর বা ক্লায়েন্ট প্রশ্ন তোলে যে "আপনার রিপোর্টে এই সিকিউরিটি দুর্বলতাটি কেন আসেনি?"—তখন আপনি এই সেকশনটি দেখিয়ে বলতে পারবেন যে, "আমাদের ওই সিস্টেমের অ্যাক্সেস বা পলিসি দেওয়া হয়নি (Limitation), যা রিপোর্টে আগেই স্পষ্ট লেখা আছে।" এতে আপনার ওপর কোনো দায় আসবে না।
২. ভুল সিদ্ধান্ত এড়ানো: ম্যানেজমেন্ট রিপোর্ট পড়ে বুঝতে পারবে কোন ফলাফলগুলো ১০০% প্রমাণের ভিত্তিতে তৈরি, আর কোনগুলো অনুমানের (Assumption) ওপর ভিত্তি করে লেখা। ফলে তারা সঠিক সিদ্ধান্ত নিতে পারবে।
৩. পরবর্তী অডিটের পথ সহজ করা: রিপোর্টে যখন লেখা থাকবে যে "Access Control Policy - Not Provided", তখন পরবর্তী ধাপে কোম্পানির টিম জানবে যে তাদের এই ডকুমেন্টটি খুঁজে বের করতে হবে বা নতুন করে তৈরি করতে হবে।
৪. রিপোর্টের গ্রহণযোগ্যতা বৃদ্ধি: একজন দক্ষ GRC Analyst কখনোই অন্ধকারে ঢিল ছোড়েন না। সীমাবদ্ধতাগুলো স্বীকার করে নিলে পুরো রিপোর্টটি অনেক বেশি বিশ্বাসযোগ্য ও পেশাদার (Professional) হয়ে ওঠে।


*"ISO 27001:2022-এর Clauses 4 to 10 হলো কোর ম্যানেজমেন্ট রিকোয়ারমেন্ট, যা প্রতিটি প্রতিষ্ঠানের জন্যই বাধ্যতামূলক। তবে Annex A-এর ৯৩টি কন্ট্রোল সব প্রতিষ্ঠানের জন্য একরকমভাবে প্রযোজ্য নয়।

কোন কন্ট্রোলটি প্রযোজ্য তা নির্ধারণ করার জন্য আমি প্রথমে প্রতিষ্ঠানের Scope এবং Business Model বুঝব (যেমন—তারা কি সফটওয়্যার বানায়, নাকি ক্লাউড সার্ভিস দেয়, নাকি রিমোট অফিস)। এরপর Risk Assessment করে দেখব কোন রিস্কগুলো কমানোর জন্য কোন কন্ট্রোল প্রয়োজন, এবং ক্লায়েন্ট বা আইনি কোনো বাধ্যবাধকতা আছে কি না। সবশেষে Statement of Applicability (SoA) ডকুমেন্টে যুক্তিসহ (Justification) লিখে দেব কেন একটি কন্ট্রোল নেওয়া হলো আর কেন অন্যটি বাদ দেওয়া হলো।"*

শুধু মনে রাখুন ক্লজ ৪–১০ মানে ম্যানেজমেন্ট, আর Annex A মানে ৪টি বিষয়—People, Physical, Organizational, Technological।

কমন ৫-৬টি কন্ট্রোল জেনে রাখুন: ইন্টারভিউতে উদাহরণ দেওয়ার জন্য কয়েকটি জনপ্রিয় কন্ট্রোলের নাম মাথায় রাখুন—যেমন: Access Control, Backup, Cryptography (Encryption), Secure Coding, Incident Management, Supplier Security। এগুলো প্রায় সব আইটি কোম্পানিতেই লাগে।

Section 8: Assumptions and Limitations

প্রশ্ন: কোন তথ্য নিশ্চিত এবং কোন তথ্য এখনো যাচাই করা হয়নি?

দুই ধরনের বিষয় আলাদা রাখবে।
- Assumption: Assessment পরিকল্পনার জন্য অস্থায়ীভাবে গ্রহণ করা ধারণা।
- Limitation: Assessment-এর সীমাবদ্ধতা, যেমন Evidence না পাওয়া বা System Access না থাকা।
  
উদাহরণ:
বিষয়	Status
Company Business Profile	Publicly Available
Employee Count	Not Verified
AWS Environment	Simulated
Access Control Policy	Not Provided
Internal Audit Records	Not Available

এখানে কখনোই Not Available-কে Non-Compliant লিখবে না।

Section 9: Assessment Criteria

এখানে উল্লেখ করবে কোন Standard ও Requirements-এর বিরুদ্ধে Assessment করবে।

আমাদের Project-এর জন্য:
- ISO/IEC 27001:2022 Clauses 4–10
- ISO/IEC 27001:2022 Annex A Controls
একটি বিষয় মনে রাখবে: Annex A-এর সব Control প্রতিটি কোম্পানির জন্য স্বয়ংক্রিয়ভাবে Applicable নয়। Risk Assessment এবং SoA-এর মাধ্যমে Applicability নির্ধারণ করতে হয়।

Section 10: Approval

বাস্তবে Scope Document তৈরি করার পর:
1. তুমি Draft তৈরি করবে।
2. GRC Manager Review করবেন।
3. Relevant Department Heads Scope যাচাই করবেন।
4. Management অনুমোদন দেবে।
5. Approved Version সংরক্ষণ করবে।
নিজে Prepared, Reviewed ও Approved—তিনটি জায়গায় একই ব্যক্তির নাম বসাবে না।


ধরো, তুমি Riseup Labs-এর Software Engineering Manager-এর সঙ্গে Meeting করছ।

তুমি প্রশ্ন করবে:
Sample Stakeholder Interview Questions

Business Understanding
1. আপনার Department-এর প্রধান কাজগুলো কী?
2. Software Development Process কীভাবে পরিচালিত হয়?

Information Assets
3. আপনারা কী ধরনের Client Information সংরক্ষণ করেন?
4. Source Code কোথায় সংরক্ষণ করা হয়?
5. গুরুত্বপূর্ণ Data-এর Owner কে?

Access Management
6. Developer-দের System Access কে অনুমোদন দেয়?
7. Employee চাকরি ছেড়ে দিলে Access কীভাবে বন্ধ করা হয়?

Security Controls
8. Code Review কি বাধ্যতামূলক?
9. Production Deployment-এর আগে Approval নেওয়া হয়?
10. Security Incident হলে কাকে Report করা হয়?

এগুলোই তোমার বাস্তব কাজের ভিত্তি হবে।



