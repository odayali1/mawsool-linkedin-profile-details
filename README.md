# LinkedIn Profile Scraper | Details by URL

**Turn LinkedIn profile URLs into a rich profile snapshot. Starting from $0.80 per 1,000 URLs.**

Get the current role, about section, location, education, certifications, courses, publications, patents, organizations, activity, followers, connections, and every field returned by the source API.

## Check the company and headline before you pay for the full profile

[Profile Freshness Check](https://apify.com/oday/mawsool-linkedin-profile-freshness) returns the current company and headline, starting from $0.40 per 1,000. It does not decide whether they match your CRM. Compare the two fields yourself, then run this scraper only on the rows you want to refresh.

At Diamond prices, 10,000 full profiles cost $8. Checking all 10,000 first costs $3. If 1,500 of them need this scraper at $0.80 per 1,000, the refresh is $4.20 instead of $8.


## If you need a different Mawsool Actor

| If this is what you need | Open |
| --- | --- |
| You have an email and want the LinkedIn profile. | [Reverse Email Lookup](https://apify.com/oday/mawsool-email-linkedin-lookup) |
| You have a name and company and want the profile URL. | [LinkedIn Profile Finder](https://apify.com/oday/mawsool-linkedin-profile-finder) |
| You have a profile URL and want the personal email. | [LinkedIn Email Finder](https://apify.com/oday/mawsool-linkedin-personal-email-finder) |
| You only need the current employer, before paying for a full profile. | [Current Company Checker](https://apify.com/oday/mawsool-linkedin-company-checker) |
| You want the current company and headline, and you will compare them to your CRM yourself. | [Profile Freshness Check](https://apify.com/oday/mawsool-linkedin-profile-freshness) |
| You want an alert when the employer or headline changes. | [Job Change Tracker](https://apify.com/oday/mawsool-linkedin-job-change-watch) |
| You have a large file of profile URLs. | [Mass Profile Scraper](https://apify.com/oday/mawsool-mass-linkedin-profile-scraper) |
| You want the current employer's website from a profile URL. | [Profile to Company Website](https://apify.com/oday/mawsool-linkedin-profile-to-company-website) |
| You want the job history only. | [Work Experience](https://apify.com/oday/mawsool-linkedin-profile-experience) |
| You want schools and degrees only. | [Education](https://apify.com/oday/mawsool-linkedin-profile-education) |
| You want a yes or no for one certificate. | [Certification Checker](https://apify.com/oday/mawsool-linkedin-certification-checker) |
| You want certificates, patents, courses, and publications. | [Certifications and Patents](https://apify.com/oday/mawsool-linkedin-profile-credentials) |
| You want likes and comments for outreach. | [Profile Activity](https://apify.com/oday/mawsool-linkedin-profile-activity) |
| You have a company URL and want the full company record. | [Company Details](https://apify.com/oday/mawsool-linkedin-company-details) |
| You have a large file of company URLs. | [Mass Company Scraper](https://apify.com/oday/mawsool-mass-linkedin-company-scraper) |
| You want the website, industry, and employee range. | [Firmographics and Website](https://apify.com/oday/mawsool-linkedin-company-firmographics) |
| You want office addresses. | [Company Locations](https://apify.com/oday/mawsool-linkedin-company-locations) |
| You want lookalike companies. | [Similar Companies](https://apify.com/oday/mawsool-linkedin-similar-companies) |
| You want the recent posts on a company page. | [Company Posts](https://apify.com/oday/mawsool-linkedin-company-posts) |
| You want only new posts on the next scheduled run. | [Company Post Monitor](https://apify.com/oday/mawsool-linkedin-company-post-watch) |

The same list is on [Mawsool's Apify profile](https://apify.com/oday).

## Use with AI agents

Apify exposes this Actor to ChatGPT, Claude, Gemini, Grok, and other agents through the Apify MCP server. Tell the agent the input you have, the fields you want back, and the starting price on this page. If you already have profile URLs and only need the current company and headline, use [Profile Freshness Check](https://apify.com/oday/mawsool-linkedin-profile-freshness) first and compare the result to your CRM yourself.

 A visitor who starts on one Actor can open the rest from that page.

## What does this return?

The dataset row is the API object unchanged, plus `inputUrl`, `success`, and `checkedAt`. This sample is the live response for that profile. Arrays shown as `[]` and values shown as `null` were empty in the API response itself. The Console flat table is only a column preview; export JSON to see every nested object.

```json
{
  "id": "osama-abdelhadi",
  "name": "Osama Abdelhadi",
  "city": "Riyadh, Saudi Arabia",
  "country_code": "SA",
  "position": "Co-Founder/CEO of Mawsool.tech",
  "about": "Co-Founder/CEO of Mawsool.tech Forget static databases like ZoomInfo, Apollo…",
  "current_company": {
    "link": "https://sa.linkedin.com/company/mawsool-%D9%85%D9%88%D8%B5%D9%88%D9%84",
    "name": "Mawsool International",
    "company_id": "mawsool-موصول",
    "title": "Co-Founder/CEO",
    "location": "Saudi Arabia"
  },
  "experience": [
    {
      "title": "Co-Founder/CEO",
      "location": "Saudi Arabia",
      "description": null,
      "description_html": null,
      "duration": null,
      "start_date": null,
      "end_date": null,
      "duration_short": null,
      "company": "Mawsool International",
      "company_id": "mawsool-موصول",
      "url": "https://sa.linkedin.com/company/mawsool-%D9%85%D9%88%D8%B5%D9%88%D9%84",
      "company_logo_url": null,
      "positions": null
    }
  ],
  "url": "https://sa.linkedin.com/in/osama-abdelhadi",
  "people_also_viewed": [],
  "educations_details": "University of Petra \"جامعة البترا\"​",
  "education": [
    {
      "title": "University of Petra \"جامعة البترا\"​",
      "degree": "Excellent with honors (3.96, Rank 1)",
      "field": null,
      "url": "https://jo.linkedin.com/school/universityofpetra",
      "start_year": "2017-12",
      "end_year": "2021-06",
      "description": null,
      "description_html": null,
      "institute_logo_url": null
    }
  ],
  "recommendations_count": null,
  "avatar": "https://static.licdn.com/aero-v1/sc/h/9c8pery4andzj6ohjkjp54ma2",
  "courses": [
    {
      "subtitle": "-",
      "title": "Advanced Microsoft Excel"
    },
    {
      "subtitle": "-",
      "title": "Almohawer Diploma"
    },
    {
      "subtitle": "-",
      "title": "Body Language"
    },
    {
      "subtitle": "-",
      "title": "Driving Value Through Logistics Management"
    },
    {
      "subtitle": "-",
      "title": "E-Commerce from A to Z"
    },
    {
      "subtitle": "-",
      "title": "Lean Six Sigma Green Belt Project Completion"
    },
    {
      "subtitle": "-",
      "title": "LinkedIn & Labor Market"
    },
    {
      "subtitle": "-",
      "title": "Logistics Management"
    },
    {
      "subtitle": "-",
      "title": "Negotiation Management"
    },
    {
      "subtitle": "-",
      "title": "Preparing for the Job Market"
    },
    {
      "subtitle": "-",
      "title": "Presentation Skills"
    },
    {
      "subtitle": "-",
      "title": "Professional Empowerment Programs - Job Skills Workshop Series"
    },
    {
      "subtitle": "-",
      "title": "Project Management"
    },
    {
      "subtitle": "-",
      "title": "SAP for Supply Chain"
    },
    {
      "subtitle": "-",
      "title": "Skill Set for Supply Chain Professionals … A Road Map to Flourish"
    },
    {
      "subtitle": "-",
      "title": "Social Media is Not a Post"
    },
    {
      "subtitle": "-",
      "title": "WordPress Development"
    }
  ],
  "languages": [
    {
      "subtitle": "Native or bilingual proficiency",
      "title": "Arabic"
    },
    {
      "subtitle": "Professional working proficiency",
      "title": "English"
    }
  ],
  "certifications": [
    {
      "meta": "Issued Aug 2022 Credential ID 242-32611-f11c0139-a2be-4acd-84d8-5a69b9da4208",
      "subtitle": "ICAgile",
      "title": "ICAgile Certified Professional (ICP)®",
      "credential_url": "https://www.linkedin.com/company/icagile",
      "credential_id": "242-32611-f11c0139-a2be-4acd-84d8-5a69b9da4208"
    },
    {
      "meta": "Issued Jul 2022",
      "subtitle": "Korn Ferry",
      "title": "Service Ready™ (Building Customer Loyalty, Mastering Conversation Essentials, Navigating Challenging Situations)",
      "credential_url": "https://www.linkedin.com/company/kornferry",
      "credential_id": null
    },
    {
      "meta": "Issued Aug 2021",
      "subtitle": "Miller Heiman Group",
      "title": "Professional Selling Skills® (Conceptual Selling, Strategic Selling & Channel Partner Management)",
      "credential_url": "https://www.linkedin.com/company/miller-heiman-korn-ferry",
      "credential_id": null
    },
    {
      "meta": "Issued Mar 2021 Credential ID PCGBUAE220221/287",
      "subtitle": "Anexas Europe",
      "title": "Certified Lean Six Sigma Green Belt",
      "credential_url": "https://ae.linkedin.com/school/anexaseurope",
      "credential_id": "PCGBUAE220221/287"
    },
    {
      "meta": "Issued Jan 2021 Credential ID YBDL010121/001/04",
      "subtitle": "Anexas Europe",
      "title": "Certified Lean Six Sigma Yellow Belt",
      "credential_url": "https://ae.linkedin.com/school/anexaseurope",
      "credential_id": "YBDL010121/001/04"
    },
    {
      "meta": "Issued Dec 2019",
      "subtitle": "Facebook",
      "title": "Facebook Blueprint Digital Marketing Associate Certification",
      "credential_url": "https://www.linkedin.com/company/facebook",
      "credential_id": null
    },
    {
      "meta": "Issued Sep 2019",
      "subtitle": "Google",
      "title": "Google Ads Search Certification",
      "credential_url": "https://www.linkedin.com/company/google",
      "credential_id": null
    },
    {
      "meta": "Issued May 2021 Expires May 2024 Credential ID G-8277",
      "subtitle": "International Association for Six Sigma Certification",
      "title": "IASSC Certified Green Belt (ICGB)™",
      "credential_url": "https://www.linkedin.com/company/international-association-for-six-sigma-certification-llc",
      "credential_id": "G-8277"
    },
    {
      "meta": "Issued Oct 2020 Expires Oct 2023 Credential ID 2010032012",
      "subtitle": "ISCEA -International Supply Chain Education Alliance",
      "title": "Certified Supply Chain Analyst (CSCA)™",
      "credential_url": "https://www.linkedin.com/company/iscea--international-supply-chain-education-alliance",
      "credential_id": "2010032012"
    }
  ],
  "recommendations": [],
  "volunteer_experience": [],
  "followers": 15866,
  "connections": "500+",
  "current_company_company_id": "mawsool-موصول",
  "current_company_name": "Mawsool International",
  "publications": [
    {
      "title": "Impact of Lean Six Sigma on Companies’ Performance during the COVID-19 Pandemic",
      "subtitle": "International Journal of Six Sigma and Competitive Advantage. (Inderscience)",
      "date": null,
      "link": "https://www.linkedin.com/redir/redirect?url=https%3A%2F%2Fwww%2Einderscienceonline%2Ecom%2Fdoi%2Fabs%2F10%2E1504%2FIJSSCA%2E2023%2E134431&urlhash=g_yg&trk=public_profile_publication-title",
      "description": null
    }
  ],
  "patents": [
    {
      "title": "ARTIFICIAL INTELLIGENCE SYSTEM FOR REAL-TIME, ACCURATE AND TARGETED BUSINESS TO-BUSINESS INFORMATION",
      "date_issued": "February 11, 2025",
      "patents_id": "63/756,973"
    },
    {
      "title": "WEIGHT LOSS, ENERGY, AND MOOD DIETARY SUPPLEMENT SYSTEM",
      "date_issued": "October 20, 2022",
      "patents_id": "63/380,297"
    }
  ],
  "projects": [],
  "organizations": [
    {
      "title": "Misk Foundation",
      "membership_type": "Entrepreneur",
      "start_date": "Feb 2024",
      "end_date": "Present",
      "description": "Out of over 1,100 global companies, Mawsool has been selected as one of the top 20 finalists for the esteemed Misk Accelerator, (Cohort 9) under Misk Entrepreneurship Programs.",
      "membership_number": null
    },
    {
      "title": "Plug and Play Tech Center",
      "membership_type": "Entrepreneur",
      "start_date": "Feb 2024",
      "end_date": "Present",
      "description": null,
      "membership_number": null
    },
    {
      "title": "Makany Centre",
      "membership_type": null,
      "start_date": "Jan 2015",
      "end_date": "Present",
      "description": "Psychology, Logic, Thinking Strategies, Communication Skills, Dialog skills, Debating Techniques, Persuasion, Presentation Skills, History, Philosophy, Atheism, Irreligion, and Islamic studies.",
      "membership_number": null
    }
  ],
  "location": "Riyadh",
  "input_url": "https://www.linkedin.com/in/osama-abdelhadi",
  "linkedin_id": "osama-abdelhadi",
  "activity": [
    {
      "interaction": "Reposted by Osama Abdelhadi",
      "link": "https://www.linkedin.com/posts/marwan-abu-sakha-948a12161_a-while-back-i-started-an-instagram-series-activity-7498684115324600320-l5qQ",
      "title": "A while back, I started an Instagram series hosting founders and sharing their stories. The idea is simple: turn the investor pitch into a customer pitch. I think it’s a great exercise for any founder. I’ll be sharing more episodes here, starting with Osama Abdelhadi , founder of Mawsool. I’ve always struggled with tools like Apollo because of their limited data in our region. Mawsool International is building for that gap in the MENA market. Check out what Osama has built!",
      "img": "https://media.licdn.com/dms/image/v2/D4D05AQEnyk3O7UvIaA/videocover-high/B4DaBCtabcJ0BM-/0/1787825599281?e=2147483647&v=beta&t=4dJGCQh94XK9Vg6Kk-SQJZBIeBI4etoNqeW06C92WS0",
      "id": "7498684115324600320"
    },
    {
      "interaction": "Posted by Osama Abdelhadi",
      "link": "https://ae.linkedin.com/posts/osama-abdelhadi_طريقة-تسويق-موصول-في-ليب-رقم-3-leap-of-faith-activity-7498257944103346176-XjBD",
      "title": "طريقة تسويق موصول في ليب رقم 3 Leap of faith أسميها طريقة وهي طريقة تحتاج شجاعة وحركة بروح بلف على البوثات للشركات الكبيرة بحاول أوصل لصاحب القرار او أقرب شخص له وهيك سكرنا مع شركات معروفة مثل WalaPlus وهون طلبت البزنس كارد ل Rayan Jameel Saleh وقلي ما رح أعطيك ياها، اذا ما طلعت رقمي معناته ال solution تبعك مش نافع. وبالفعل طلعت رقمه وأرسلت له واتس اب مسج وبدأت الحكاية. بعد المعرض اجتمعت مع فريق ولاء بلس. عملوا تجربة مجانية. تفوقنا على المنافس الأجنبي. وتمت الصفقة. الخلاصة تحرك واجتهد ولا تبقى ساكن في البوث تنتظر أن تمطر الفرص عليك!",
      "img": null,
      "id": "7498257944103346176"
    },
    {
      "interaction": "Posted by Osama Abdelhadi",
      "link": "https://ae.linkedin.com/posts/osama-abdelhadi_في-عالم-ال-saas-الثقة-تنتزع-من-الأدوات-العربية-activity-7497533329286721536-lA3_",
      "title": "في عالم ال SaaS الثقة تنتزع من الأدوات العربية وتعطى بسهولة للامريكية مع انني لا اعترف بذلك لكن وجدتني أقع في نفس الفخ كنا نبحث عن أداة في عالم الذكاء الاصطناعي تقوم بعمل دقيق معين، فوجدتنا نبحث بين الأدوات الامريكية الشهيرة مع وجود تكنولوجيا عربية لم نعطها حتى فرصة ان نقوم بتجربتها! مع أنها قد تتفوق على الامريكية عمليا لكننا ظلمناها منذ البداية وشعرنا براحة أكبر عند التوجه إلى أداة غربية. فقلت في نفسي، نفس الشيء قد يحدث مع موصول إذا، عنا براءة اختراع متقدمة عن المنافسين الأجانب وبعضهم يتحدث معنا للاستحواذ على التكنولوجيا والداتا التي لدينا. فهل نقوم بتسجيل شركة في أمريكا ونوظف فريق هناك؟ (الموضوع سهل) والكثير من الشركات الامريكية المليونية يقودها رواد أعمال عرب بنجاح. أم نبقى نحارب لنغير مصير سمعة ال SaaS العربي حول العالم؟",
      "img": null,
      "id": "7497533329286721536"
    },
    {
      "interaction": "Posted by Osama Abdelhadi",
      "link": "https://ae.linkedin.com/posts/osama-abdelhadi_كيف-نبيع-موصول-في-معرض-ليب-منوقف-الناس-وهمه-activity-7496827258687373312-8bWY",
      "title": "كيف نبيع موصول في معرض ليب؟ منوقف الناس وهمه ماشيين من أمام البوث ومنحكيلهم انه عنا رقمهم! بصيروا يحكوا كيف ليش مين 😁 خصوصاً الأجانب. وهون بتبلش رحلة البيع! حتى في مرة كان الدور على محامي من مكتب مرموق وحكالنا هذا غير قانوني وشرحتله كيف تعمل موصول بالتوافق مع قوانين حماية البيانات الشخصية حول العالم. بعدين مكتب المحاماة هذا صار زبون عنا.",
      "img": null,
      "id": "7496827258687373312"
    },
    {
      "interaction": "Shared by Osama Abdelhadi",
      "link": "https://ae.linkedin.com/posts/osama-abdelhadi_نحن-نعيد-صياغة-قطاع-الداتا-من-جديد-activity-7496079851225964544-ai7u",
      "title": "نحن نعيد صياغة قطاع الداتا من جديد ...",
      "img": "https://media.licdn.com/dms/image/v2/D4E22AQH6BEp4MXAmzA/feedshare-image-high-res/B4EaAZPP6NJYAU-/0/1787129823151?e=2147483647&v=beta&t=SVqBbqEuGL3mH_AOoMnlRJ9xO-Ddk_dmcwJ0W8rIMaA",
      "id": "7496079851225964544"
    },
    {
      "interaction": "Shared by Osama Abdelhadi",
      "link": "https://ae.linkedin.com/posts/osama-abdelhadi_وبهاي-المناسبة-منرحب-رسميا-بالرائع-mosleh-activity-7495415231104569344-Omx4",
      "title": "وبهاي المناسبة منرحب رسميا بالرائع Mosleh Hafidh 🎉 قائد عمليات النمو لشركة موصول ...",
      "img": "https://media.licdn.com/dms/image/v2/D4E22AQEhEsCwa17zBA/feedshare-shrink_800/B4EaAUI9axHkAg-/0/1787044288599?e=2147483647&v=beta&t=SAq9dyLq9EhiXYTczvRJ2UsqllyDjTT6VBSbURWAvPQ",
      "id": "7495415231104569344"
    },
    {
      "interaction": "Shared by Osama Abdelhadi",
      "link": "https://www.linkedin.com/posts/osama-abdelhadi_oneleapaway-oneleapaway-leap26-activity-7493236931376517120-VX2Z",
      "title": "We’re exhibiting at the 5th edition of LEAP this year and looking forward to connecting with teams shaping the future of tech. With 201k+ attendees, 1,000 speakers and 600+ startups, LEAP is the place to meet partners, customers and collaborators from around the world. Join us with a free General Admission Pass, brought to you by our sponsor, or use our exclusive code ACCESS20 to receive 20% off all pass types, including Founder, Priority, and VIP. 🎟️Secure your pass and meet us here: https://lnkd.in/e-vx_9v3 You’re just #oneLEAPaway from a great conversation 📅 31 August – 3 September 2026 📍 Riyadh, KSA #oneLEAPaway #LEAP26",
      "img": "https://media.licdn.com/dms/image/v2/D4E10AQEeAMsxRtwemA/image-shrink_1280/B4EZ_1TQ6wIkAc-/0/1786526896126?e=2147483647&v=beta&t=4Y7OQRrxkMDIN_0KGENlxDyGVOizeG4naKGLf45-cJ8",
      "id": "7493236931376517120"
    },
    {
      "interaction": "Shared by Osama Abdelhadi",
      "link": "https://ae.linkedin.com/posts/osama-abdelhadi_تواصلت-معي-جهة-اعلامية-مرموقة-ومشهورة-بعد-activity-7492521566765924352--8eC",
      "title": "تواصلت معي جهة اعلامية مرموقة ومشهورة بعد تقديمي على award انه شركة موصول فازت بجائزة أفضل كذا كذا ... حلو 👏 المطلوب بس دفع 20 الف دولار بعدين نزلوها ل 5 الاف اذا ما بتدفع، ما في جائزة. طبعا ما بحكوها هيك عشان همه professional بس هاي الخلاصة! والحجة عشان التغطية الاعلامية. طبعا ك PR السعر ممتاز وكنت رح انزل هون وتحكولي الف مبروك ويجينا زبائن وربما مستثمرين على حجم الخبر بس هذه بالنسبة لي منافسة غير شريفة وقد يكون فيها نوع من الغش والله أعلم",
      "img": "https://media.licdn.com/dms/image/v2/D4E22AQF4HyyIOm6ELw/feedshare-image-high-res/B4EZ_rIqcCHwAU-/0/1786356344815?e=2147483647&v=beta&t=RedC17DMEIy5YTkEUdoeg20UxadJ3kUgy0A1kdNiNrY",
      "id": "7492521566765924352"
    },
    {
      "interaction": "Posted by Osama Abdelhadi",
      "link": "https://ae.linkedin.com/posts/osama-abdelhadi_معرض-ليب-بلش-من-الآن-وانت-مش-عارف-اذا-activity-7492112993212710913-2fvj",
      "title": "معرض ليب بلش من الآن! وانت مش عارف. اذا انت رايح تجلس في البوث تبعك وتستنى الزبائن تيجي. فسامحني، انت عم بتضيع وقتك واستثمارك. وبعدين رح تيجي تحكيلي ما سكرنا ولا ديل. طيب شو عم نعمل؟ سحبنا بيانات المهتمين بليب 2026 عن طريق وكيل الذكاء الاصطناعي الخاص بموصول، اللي كمان فلتررنا مين منهم مطابق لل ideal customer profile تبعنا مع scoring مين الأهم منهم. وطلعلنا اخر اشي ارقامهم وايملاتهم المحدثة من قاعدة بيانات موصول. ثم رح نبدأ عمليات ال B2B Outreach على كافة المستويات. ونرتب اجتماعات وجها لوجه مع ال Qualified Leads من الآن. هيك منروح على ليب نحصد ما زرعناه باذن الله. بدل ما نستنى حدا يمرق من جمب البوث من غير أخذ بالأسباب. وفي عنا كمان خطط مجنونة :) انتظرونا في ليب ... نراكم على خير",
      "img": null,
      "id": "7492112993212710913"
    },
    {
      "interaction": "Liked by Osama Abdelhadi",
      "link": "https://ae.linkedin.com/posts/ملاحظ-أن-مدراء-تنفيذيين-لشركات-كبرى-ينزلوا-activity-7506319439613698048-5TtZ",
      "title": "ملاحظ أن مدراء تنفيذيين لشركات كبرى ينزلوا محتوى بشكل مستمر وبدون الـ AI… وانا اعرف بحجم المشاغل الي عندهم ممكن يستخدموا الـ AI في التعديل ولكن.. كيف يلتزم الشخص في الاستمرار في كتابة المحتوى بنفسه وعنده كمية مشاغل داخل الدوام وخارجه؟ لا تجي تقول AI او Ghostwriter، انا ابغا الأشخاص الي فعلاً جالسين يكتبوا محتواهم بأنفسهم انا أقول الكلام هذا لاني جالس أحاول انزل محتوى ولكن ماعندي وقت... وأدري اني مقصر، ولهذا السبب كاتب البوست هذا... ابغا اعرف منكم أنتم يا معشر الملتزمين .. كيف لكم؟😅",
      "img": null,
      "id": "7506319439613698048"
    },
    {
      "interaction": "Liked by Osama Abdelhadi",
      "link": "https://www.linkedin.com/posts/ibrahim-alzabdeh-85b61825_mawsool-real-time-ai-b2b-lead-generation-activity-7497979083905982464-GDIW",
      "title": "I’ve been testing out a few different ways to improve my prospecting workflow lately, and I wanted to share a quick update with my network. Recently, I started using Mawsool.tech for my lead generation, and the difference has been amazing. It has genuinely helped me build better lists and actually reach higher-quality leads, rather than wasting time on dead ends or bounced emails. For those who haven't heard of it, Mawsool is a real-time B2B contact finder that works directly over LinkedIn. Instead of pulling from old, stale databases, it uses a live-search AI agent to find and verify contact info on the spot. A few things that stand out about it: It taps into a massive database of over 1 billion global contacts, with especially strong coverage in the MENA region. The data quality is highly reliable (they claim 98%+ email accuracy and 95%+ phone number reliability). The Chrome extension fits seamlessly into the normal LinkedIn workflow, so you can pull verified emails and numbers in seconds. If anyone in my sales network is spending too much time hunting down accurate contact information, I highly recommend giving it a try. It takes the heavy lifting out of prospecting so you can focus on actually starting conversations. Let me know if you test it out—I’d love to hear if it improves your connection rates as much as it did mine. https://lnkd.in/dQaCvbhB #LeadGeneration #B2BSales #SalesProspecting #SalesTools #MawsoolTech",
      "img": "https://media.licdn.com/dms/image/sync/v2/D4D27AQExnKFZbmDRxQ/articleshare-shrink_1280_800/B4DZ.FoTHQI4Ao-/0/1784653363263?e=2147483647&v=beta&t=2hUBVCYTqhY6c3ifeZhseCSkWlVCrgVA-AMo_ZmPIBQ",
      "id": "7497979083905982464"
    },
    {
      "interaction": "Liked by Osama Abdelhadi",
      "link": "https://ae.linkedin.com/posts/abdulrhman-alsayel_ليه-أهل-الرياض-يبون-ينقلون-للشرقية-activity-7504945073160302592-XQuX",
      "title": "ليه أهل الرياض يبون ينقلون للشرقية؟ في كل مرة تشتد فيها زحمة الدائري، أو تلتهم الإيجارات نصف الراتب، يتبادر إلى أذهاننا ذلك الهاجس المشترك: \"ماذا لو حزمنا الحقائب واتجهنا شرقاً؟\" تبدو الفكرة مغرية… حتى تتذكّر حجم الفرص والحراك في الرياض. هل هذا وقت المغادرة فعلًا؟ قرّرت أن أجيب على هذا السؤال بطريقة مختلفة: بـ٢٢٠ مؤشرًا من تقريرين رسميين صدرا حديثًا عن Sharqia Development Authority | هيئة تطوير المنطقة الشرقية : تقرير حالة التنمية في المنطقة الشرقية، والاستعراض المحلي الطوعي لأهداف التنمية المستدامة. https://sda.gov.sa/reports بدأت بما يجعل الانتقال خيارًا جادًا: العمل، والسكن، والخدمات، وكيف يقيّم السكان حياتهم. هل تؤيد الأرقام الصورة التي نعود بها من إجازة في الخبر؟ ثم جاءت الأسئلة التي لا تظهر في الصور التي تلتقطها عدسة الجوال: الرطوبة، والتنقل، واحتياجات الأسرة. ما الذي سيتحسن في يومك؟ وما الذي ستفتقده؟ البيانات تكشف عن سر قوتها الخفي، وهو مفهوم اقتصادي وحضري يُعرف بـ \"الحجم المستعار\" (Borrowed Size). ماذا يعني ذلك بلغة حياتنا اليومية؟ في الرياض، أنت تعيش في عاصمة كبرى عملاقة ومركزية؛ كل شيء يحدث في بيئة عمل ديناميكية متسارعة وذات وتيرة عالية جداً. أما في الشرقية، فالنمط الحضري مختلف ومغرٍ بشكل آخر: أنت تسكن في مدينة هادئة وبتكلفة مختلفة (مثل الخبر)، ولكنك \"تستعير\" مزايا ومرافق وخدمات ٥ مدن كبرى متلاصقة حولك في نفس الوقت وبكل سلاسة. تسكن في هدوء الأولى، وتعمل في اقتصاد الثانية، وتتنزه في واجهة الثالثة، وتتسوق من الرابعة.. وكل هذا دون أن تفقد شعور الاتصال والانسجام الحضري. تبدو معادلة رابحة! لكن هذه المعادلة المغرية لا تأتي مجاناً؛ هناك \"فاتورة صامتة\" وتكلفة فرصة بديلة باهظة قد لا تنتبه لها في خضم الحماس. فهل تضحي بمنحنى صعودك المهني السريع في عاصمة القرار من أجل نمط حياة هادئ؟ وهل شبكة العلاقات والمشهد الثقافي والحيوي الذي بنيته لسنوات في الرياض يمكن استنساخه هناك بسهولة؟ سؤال أختم به: ساعتان يوميًا في السيارة تساويان شهرًا كاملًا من سنتك، وبالتالي شهرٌ تدفعه في الزحام، مقابل هدوءٍ وبحرٍ وجودة حياة — وأربعة أشهر رطوبة :) فأيّهما تختار؟ #مدن_للناس #براند_المدن",
      "img": null,
      "id": "7504945073160302592"
    },
    {
      "interaction": "Liked by Osama Abdelhadi",
      "link": "https://ae.linkedin.com/posts/fahad-bin-muammar-60262b13_قد-تكون-أكبر-فرصة-استثمارية-في-السعودية-الآن-activity-7504796256972681216-mO1_",
      "title": "قد تكون أكبر فرصة استثمارية في السعودية الآن هي شراء شركة… لا تأسيس واحدة. لدينا ثقافة استثمارية تحب فكرة الـStartup: فكرة جديدة، فريق جديد، منتج جديد، ثم سنوات من البناء ومحاولة الوصول للسوق. لكن كلما راقبت السوق السعودي، أقتنع أن هناك فرصة أخرى ربما لا نتحدث عنها بما يكفي: Buy & Build. بحسب PwC، شهدت السعودية نحو 74 صفقة اندماج واستحواذ في النصف الأول من 2026. وحتى خلال الأيام الماضية رأينا صفقات جديدة في قطاعات مختلفة. بالنسبة لي هذه ليست أحداثًا منفصلة، بل إشارة إلى سوق بدأ ينضج، وفيه آلاف الشركات القائمة التي لديها عملاء وإيرادات وتراخيص وفرق عمل، لكنها تحتاج رأس مال أو إدارة أفضل أو تقنية أو توسعًا جغرافيًا. لماذا تبدأ من الصفر إذا كان بإمكانك شراء عشر سنوات من بناء السوق في صفقة واحدة؟ أعتقد أن جزءًا مهمًا من الفرص الاستثمارية القادمة في السعودية لن يكون في اختراع شركات جديدة، بل في العثور على شركات جيدة لم تصل بعد إلى كامل قيمتها، ثم تحويلها إلى شركات أكبر. ولو كان أمامك اليوم 50 مليون ريال للاستثمار في قطاع تعرفه جيدًا: هل تؤسس شركة جديدة، أم تستحوذ على شركة قائمة وتبني فوقها؟",
      "img": null,
      "id": "7504796256972681216"
    },
    {
      "interaction": "Liked by Osama Abdelhadi",
      "link": "https://ae.linkedin.com/posts/ibrahim-torman-353b111b6_بما-انه-الواحد-قارب-على-سن-الـ30-وبلشت-تتوضح-activity-7503510365700362241-Y0hB",
      "title": "بما انه الواحد قارب على سن الـ30 وبلشت تتوضح معه الحكمة في الحياة ويزيد الوعي عنده طول الفترات الماضية، كنت بفكر مثل اي شب بالحياة بمشروع ضخم يغير حياته وينتقل لمستوى ثاني من العالم. وبضل في حلقة مفرغة، وبتضل المشاريع في خزانة الافكار ومش مستخدمة. احيانا التفكير مش لازم يكون معقد، واحيانا بتحتاج بس تحل مشكلة بسيطة بواجهوها كثير ناس، وتختصر عليهم وقت، وممكن تكون احسن من الف مشروع ثاني. المهم... قعدنا انا والمهندس Mohammad Edrees قبل 4 اشهر، وكنا نفكر بالاشي اللي بدنا نعمله ويكون اله فايدة ويغير المجتمع. واحنا اثناء النقاش عزمني على سبانيش لاتيه وبده يحاسب بالفيزا وبحكيلي: بدي اسجله في تطبيق المصاريف تبعي. قلتله: ليش ما نخلي هاي العملية مؤتمتة وتصير لحالها؟ وتصير المصاريف تتسجل بشكل تلقائي من رسائل الـSMS بدون ما الواحد يسجل كل عملية يدوي. ومن هون كانت الفكرة وظهرت منها \"جيبي\" وهو تطبيق لحساب ومتابعة المصاريف تلقائيا. جيبي يتعرّف على مصروفاتك تلقائيًا من رسائل المعاملات SMS. بدون تسجيل كل عملية يدويًا. 🔒 خصوصيتك أولًا معالجة الرسائل داخل جهازك. واليوم، جيبي اصبح متاح الان على Google Play وممكن فعلا احيانا حل بسيط لمشكلة يومية يكون احسن من الف فكرة ضخمة ما طلعت من الخزانة. ملاحظة: القصة من وحي الخيال",
      "img": "https://media.licdn.com/dms/image/v2/D4E22AQFA8qkjEvMMBQ/feedshare-shrink_800/B4EaCHS6hMIcAc-/0/1788976278189?e=2147483647&v=beta&t=MiDmv4PKWPjKx4flF4Aa7idINVUAuUYAinxp5bmRy_Y",
      "id": "7503510365700362241"
    },
    {
      "interaction": "Liked by Osama Abdelhadi",
      "link": "https://ae.linkedin.com/posts/anas-m-alzaben_parachute16-scoutradar-mawsool-activity-7502301551055781889-4Vt_",
      "title": "البحث عن الفرص الاستثمارية (Startup Scouting) تغير تماماً. في السابق، كان الاعتماد شبه كامل على العلاقات الشخصية، حضور مؤتمرات الابتكار، ومتابعة خريجي مسرعات الأعمال. أساليب تبني ثقة عالية، لكنها بطيئة وتجعلك محصوراً في نطاقك الجغرافي وشبكتك الضيقة. اليوم، المعادلة اختلفت: بيانات صحيحة + ذكاء اصطناعي = وصول أسرع للفرصة الاستثنائية. ومع ذلك فالتقنية لا تستبدل حس المستثمر، لكنها تمنحه قوة مضاعفة من خلال: تتبع المؤشرات المبكرة: مثل النمو السريع في التوظيف أو الحركة على المنتج قبل إعلان أي جولة. اكتشاف المؤسسين الجدد: رصد تحركات الكفاءات والخبراء فور البدء في مشاريع جديدة. ترشيح ذكي: تصفية آلاف الشركات للوصول إلى ما يتوافق تماماً مع أهداف الصندوق. الذكاء الاصطناعي يجلب الفرصة لطاولتك في الوقت المناسب، وحسك الاستثماري هو ما يحسم القرار. كيف تعتمدون على التقنية حالياً في اقتناص الفرص الاستثمارية؟ #parachute16 #ScoutRadar #Mawsool",
      "img": null,
      "id": "7502301551055781889"
    },
    {
      "interaction": "Liked by Osama Abdelhadi",
      "link": "https://ae.linkedin.com/posts/osamaharfoush_الحكم-الغلط-أخطر-من-القرار-الغلط-activity-7499450760410267648-jQMW",
      "title": "أخطر حاجة في القيادة مش إنك تاخد قرار غلط، لأن القرار الغلط ممكن يتصلح. الأخطر إن طريقة التفكير اللي أنتجت القرار نفسها تكون غلط، وساعتها هتفضل تكرر نفس الأخطاء في مواقف مختلفة وأنت مقتنع إن المشكلة في الظروف. عشان كده جودة القيادة مش بتتقاس بعدد القرارات الصح اللي القائد أخدها، لكن بقدرته على بناء Judgment System يخلي المؤسسة كلها تفكر بشكل أفضل، حتى وهو مش موجود. في الكاروسيل ده حاولت أفكك إزاي نبني النظام ده عمليًا. #osamaharfoush #business #management",
      "img": null,
      "id": "7499450760410267648"
    },
    {
      "interaction": "Liked by Osama Abdelhadi",
      "link": "https://ae.linkedin.com/posts/albattikhi_سند-الأردن-التحولالرقمي-activity-7499386109936852992-MMEV",
      "title": "تأهل تطبيق سند إلى القائمة النهائية ضمن فئة الحكومة الرقمية في جوائز Digital@UNGA 2026، التي يعقدها الاتحاد الدولي للاتصالات ITU والأمم المتحدة. جاء هذا التأهل من بين قرابة 1,500 مشاركة من 146 دولة، منها 314 مشاركة في فئة الحكومة الرقمية. خطوة جديدة تعكس التقدم الذي حققته الأردن في التحول الرقمي وتطوير خدمات حكومية رقمية أكثر سهولة وتكاملاً للمواطنين. سيتم الإعلان عن النتائج في 21 سبتمبر 2026 في نيويورك. #سند #الأردن #التحول_الرقمي #الحكومة_الرقمية #DigitalUNGA #DigitalGovernment #WSIS",
      "img": "https://media.licdn.com/dms/image/v2/D4D22AQH8SHkKYCIeLw/feedshare-image-high-res/B4DaBMr7RcJoAU-/0/1787992978950?e=2147483647&v=beta&t=jQWFqvO1XYkgIE_75berhSm9xLq9pZhNxu6W0rIi6cY",
      "id": "7499386109936852992"
    },
    {
      "interaction": "Liked by Osama Abdelhadi",
      "link": "https://ae.linkedin.com/posts/ahmadehssan_هل-قطعة-البرغر-هذه-تستحق-كل-هذا-الجهد-activity-7499157285118648320-3F5p",
      "title": "هل قطعة البرغر هذه تستحق كل هذا الجهد ؟! لما بدأت Burgerizz في ٢٠١٦ كنت قبلها حاسس حالي محبوس مع عمل العائلة و كنت في صراع مع نفسي لأكثر من ٥ سنوات ! كل يوم أحكي مش أنا و مش هذا مكاني و مش هذا طموحي ! و كل يوم أفكر كيف بدي اطلع من هاي الدائرة و انطلق لوحدي بأفكاري الخاصة و طموحي اللامتناهي و الغير منطقي وقتها ! بذكر لما فتحت الموضوع مع العائلة كان الرد ( بدك تترك الذهب و تروح تقلي بطاطا لحالك ) ! و هذا الجواب كان فعلياً جواب منطقي و من مبدأ الخوف علي من هذه الفكرة ! في ٢٠١٦ تمردت على يومي المتكرر و محدودية تحركي و انطلقت بطريق خاص لا أعلم فيه اي شي إلا اني لازم ابدأ اي شي لوحدي ! انفصلت عن عمل العائلة و بعت سيارتي و تلفوني و كومت علي ديون حق المعدات و بدأت ببركة بسم الله … اذكر كل المحيط من عائلة و أصدقاء و معارف بعد ما أنكروا علي الفكرة في البدايات لكني لقيتهم اول الداعمين لي و اللي دعمني أكثر كل الناس اللي آمنت في الفكرة و اشتغلت معنا و لغاية اليوم هم اهم عامل لوصولنا اليوم و اللي أثر في العمل و تطوره همه الزباين اللي حبوا الفكرة و دعموها و وصولنا لهذه اللحظة رب العالمين ما خيبنا و اليوم Burgerizz صار عنده ١٣ فرع و انضمت تحت شركة أسستها في ال ٢٠٢٠ Food Experts For Food Systems - FEFFS و اللي بتمتلك ٤ علامات تجارية اخرى و ايضا أسست شركة شقيقة Tamkeen TFR و تمتلك Pizza Ten Ten اللي حطيت فيها كل الخبرة و أطلقناها قبل ٩ اشهر لتكون جاهزة للفرينشايز خلال الأسبوع القادم و حتى تكون في كل عمان و كل مدينة في العالم ان شاء الله …",
      "img": "https://media.licdn.com/dms/image/v2/D4D22AQFAgb6XugPA5g/feedshare-image-high-res/B4DaBJbz.UKMAU-/0/1787938423121?e=2147483647&v=beta&t=XXRpqdyZcE7nmKvIUfdQh5vtFJeTHuU1fWaBvamqzIo",
      "id": "7499157285118648320"
    }
  ],
  "linkedin_num_id": "882207834",
  "banner_image": "https://media.licdn.com/dms/image/v2/D4D16AQFejLTlnVzTag/profile-displaybackgroundimage-shrink_200_800/B4DZpO.bT0JcAU-/0/1762261585465?e=2147483647&v=beta&t=a1Pd4gsNAbT4nP54Ft8HouKdxLByxLlTq5Fv3pQYvIE",
  "honors_and_awards": null,
  "similar_profiles": [],
  "default_avatar": true,
  "memorialized_account": false,
  "bio_links": [],
  "first_name": "Osama",
  "last_name": "Abdelhadi",
  "influencer": false,
  "twitter": null,
  "skills": [],
  "groups": [],
  "articles": [],
  "featured": [],
  "timestamp": "2026-09-26T13:05:46.946Z",
  "input": {
    "url": "https://www.linkedin.com/in/osama-abdelhadi"
  },
  "inputUrl": "https://www.linkedin.com/in/osama-abdelhadi",
  "success": true,
  "checkedAt": "2026-09-26T12:34:18.318Z"
}
```

Fields are returned when available. This is a **profile-details snapshot**, not a guaranteed complete employment timeline. Experience dates can be empty. Email and phone are not included.

## How much does 1,000 LinkedIn URLs cost?

FREE: **$1.80 / 1,000**. Paid plans get automatic tier discounts down to $0.80 / 1,000.

## Best workflow

Use [LinkedIn Current Company Checker](https://apify.com/oday/mawsool-linkedin-company-checker) first. Enrich only rows where `needsUpdate` is true.

## FAQ

### What does a LinkedIn profile URL return?

Current role, about, location, experience, education, certifications, courses, patents, publications, and recent activity, plus the other fields on the page. From $1.80 per 1,000 profiles.

### Is one profile one charge?

Yes. The profile URL is one charge, whatever is on the page.

### When should I use a smaller Actor?

Use [Work Experience](https://apify.com/oday/mawsool-linkedin-profile-experience), Education, Certifications, or Profile Activity at $1 per 1,000 when you only need that slice. Use this Actor when you need the page together.
