# API Documentation of Klevere

## {{baseUrl}}

```
https://app.klevere.ai:5000/api
```

## Dashboard URL

```
https://app.klevere.ai/
```
## Tutorials for Obtaining Your API Key.
1. Log in with valid credentials or sign up for an account.
2. Purchase a plan if you don't have a premium account.
3. In the bottom of the dashboard sidebar, find the profile section displaying your name and email.
4. Hover or click on this section to reveal a dropdown menu.
5. Click on "Profile Settings" to be redirected to the profile page.
6. On the profile page, locate the "API" tab and click on it.
7. Here, you will find your API key. If you don't have one, click on the rightmost button with the refresh icon to generate a new API key.
8. You can then use this API key to access our services.

## 1. Completed Performance Evaluation/Generate Performance Evaluation Report

- API Endpoint:

```
{{base_url}}/v1/workflow/generate_performance_evaluation
```

- body (Payload)

```json
{
  "contributions": "Software",
  "improvement": "Software",
  "socialMedia": "",
  "amountValue": 1,
  "outputLanguage": "English"
}
```

- Response

```json
{
  "success": true,
  "data": "Performance Evaluation\n\nEmployee Name: [Employee's Name]\nPosition: Software Developer\n\nKey Contributions:\n[Employee's Name] has consistently demonstrated exceptional technical proficiency in software development throughout the evaluation period. Their key contributions include:\n- Successfully leading the development of a critical software application that significantly improved efficiency within the team.\n- Demonstrating outstanding problem-solving skills in resolving complex technical issues, helping to streamline processes and enhance overall productivity.\n- Collaborating effectively with team members on various projects, showcasing strong communication and teamwork skills.\n- Taking the initiative to mentor junior developers, contributing to the professional growth and development of the team.\n\nArea of Improvement: Software\nWhile [Employee's Name] has excelled in their role as a Software Developer, there are opportunities for further growth and development in the following areas:\n1. Advanced Coding Skills: [Employee's Name] has shown proficiency in coding, but there is room for improvement in mastering advanced coding techniques. Enhancing expertise in coding languages such as Python, Java, or C++ would further elevate their capabilities in software development.\n2. Innovation and Creativity: Encouraging [Employee's Name] to think outside the box and explore innovative solutions to complex problems can help foster a more creative approach to software development. Encouraging experimentation and exploring new technologies could lead to breakthrough solutions.\n3. Time Management: While [Employee's Name] has met project deadlines effectively, improving time management skills can help them work more efficiently and prioritize tasks more effectively. Implementing time-tracking tools and setting clear milestones can aid in better time management practices.\n\nOverall, [Employee's Name] has shown exceptional dedication and commitment in their role as a Software Developer. With a focus on continuous learning and improvement in the identified areas, [Employee's Name] has the potential to further excel in their career and make even greater contributions to the team.\n\nI look forward to seeing [Employee's Name] grow and develop in the coming evaluation period.\n\nSincerely,\n[Your Name]\nHuman Resources Expert."
}
```

## 2. Generate HR Policy Report

- API Endpoint:

```
{{base_url}}/v1/workflow/generate_policy_design
```

- body (Payload)

```json
{
  "title": "Human Resource Policy Update",
  "outputLanguage": "English"
}
```

- Response

```json
{
  "success": true,
  "data": "Title: HR Policy Design\n\nPurpose:\nThe purpose of this HR Policy Design is to provide guidelines and standards for creating effective and compliant human resource policies within the organization.\n\nPolicy Statement:\n1. All HR policies must be in line with federal, state, and local laws and regulations to ensure legal compliance.\n2. HR policies should be clearly communicated to all employees through an accessible and transparent platform.\n3. HR policies should be reviewed regularly to reflect changes in laws, regulations, and organizational needs.\n4. HR policies should be fair, consistent, and applied equally to all employees across the organization.\n5. HR policies should support the organization's values, goals, and mission while promoting a positive work culture.\n6. HR policies should be easy to understand and follow to ensure clarity and consistency in implementation.\n7. HR policies should promote diversity, inclusion, and a safe work environment for all employees.\n8. Any deviations from HR policies must be documented and approved by HR leadership to maintain accountability.\n\nImplementation:\n1. HR leadership will be responsible for overseeing the development, implementation, and monitoring of HR policies.\n2. HR managers will be responsible for communicating and enforcing HR policies within their respective departments.\n3. Employees are expected to familiarize themselves with and adhere to HR policies to maintain a productive and compliant work environment.\n\nEnforcement:\nViolation of HR policies may result in disciplinary action, up to and including termination of employment.\n\nThis HR Policy Design is effective immediately upon approval and will be reviewed annually for updates and improvements."
}
```

## 3. Draw Up Recruitment Strategy

- API Endpoint:

```
{{base_url}}/v1/workflow/generate_recruitment_strategy
```

- body (Payload)

```json
{
  "talent": "Software engineer",
  "socialMedia": "",
  "amountValue": 1,
  "outputLanguage": "English"
}
```

- Response

```json
{
  "success": true,
  "data": "To attract top software engineering talent, we will need to implement a multifaceted recruitment strategy that will set us apart from our competitors. This strategy will focus on building a strong employer brand, leveraging various recruitment channels, and creating an engaging candidate experience.\n\nFirst, we will need to showcase our company culture and values through our employer branding efforts. This can include highlighting employee testimonials, showcasing our work environment, and emphasizing our commitment to innovation and professional development.\n\nNext, we will leverage multiple recruitment channels to reach potential candidates. This can include online job boards, social media platforms, tech-specific forums, and industry networking events. By casting a wide net, we can increase our chances of attracting the best talent in the software engineering field.\n\nLastly, we will ensure that our recruitment process is streamlined and engaging for candidates. This can include providing prompt feedback, offering a transparent view of our company culture and growth opportunities, and providing a positive candidate experience from initial application to final offer.\n\nBy implementing these strategies, we can position ourselves as a top employer for software engineers and attract the best talent in the industry to join our team."
}
```

## 4. Screen CV

- API Endpoint:

```
{{base_url}}/v1/workflow/generate_cv_screening
```

- body (Payload)

```json
{
  "pdf_resume": "https://klevere-pdf-storage.s3.eu-central-1.amazonaws.com/Junior_software_developer.pdf",
  "job_description": "Software developer",
  "socialMedia": "",
  "amountValue": 1,
  "outputLanguage": "English"
}
```

- Response

```json
{
  "success": true,
  "data": "**Candidate's Resume Summary:** \nSalma Khan is a junior software developer with a BA (Hons) in Computer Science and experience as an Accounts Assistant at a firm where she worked on system maintenance, testing, support, and development. She has skills in SQL, C++, and .NET among others, and is seeking a software developer role to further her career.\n\n**Detailed Comparison:**\n- **Skills:** Salma has experience in SQL which is a crucial skill for a software developer. She also has exposure to C++ and .NET, aligning with the job requirements.\n- **Experiences:** While her role as an Accounts Assistant involved software support and testing, it lacks direct experience in coding applications and mobile applications development.\n- **Qualifications:** Salma holds a BA in Computer Science, which is relevant to the software developer position.\n- **Unique Aspects:** Salma's ability to communicate complex issues and manage projects independently could be valuable contributions to the team.\n\n**Compatibility Rating:** 7/10\nSalma's strong skills in SQL, C++, and .NET, coupled with her academic background in Computer Science, make her a good fit for the software developer role. However, her lack of direct experience in coding applications and mobile development slightly lowers her compatibility rating.\n\n**Recommendation:**\nConsidering Salma's technical skills, academic qualifications, and the potential she brings in terms of communication and project management, I recommend that the employer consider her for an interview. With the right training and support, Salma has the potential to excel in the software developer role and contribute positively to the team."
}
```

## 5. Create LinkedIn Candidate

- API Endpoint:

```
{{base_url}}/v1/workflow/generate_linkedin_screening
```

- body (Payload)

```json
{
  "linkedin_url": "https://linkedin.com/in/sishufol",
  "job_description": "Software engineering",
  "undefined": "",
  "socialMedia": "",
  "amountValue": 1,
  "outputLanguage": "Hindi"
}
```

- Response

```json
{
  "success": true,
  "data": "**Candidate's Resume Summary**:\nSohidul Islam is a Full Stack Developer with expertise in MERN stack development. He has experience working at Mediusware Ltd. as a Software Engineer and has also been a Full Stack Developer at Self Employed. Sohidul holds a Bachelor of Science degree in Computer Science from Port City International University Bangladesh.\n\n**Detailed Comparison**:\n- **Skills**: The candidate's resume mentions proficiency in MongoDB, ExpressJS, ReactJS, and NodeJS, which are relevant skills for a Software Engineering role.\n- **Experiences**: Sohidul has experience working as a Software Engineer and a Full Stack Developer, which align well with the Software Engineering job description.\n- **Qualifications**: The candidate holds a Bachelor of Science degree in Computer Science, which meets the educational requirement for a Software Engineering position.\n- **Unique Aspects**: Sohidul's experience in UI/UX design, problem-solving skills, and emphasis on collaboration and teamwork are additional strengths he brings to the role.\n\n**Compatibility Rating**: 9/10\nThe candidate demonstrates a strong alignment with the job description in terms of skills, experiences, and qualifications. Sohidul's background in MERN stack development, experience in software engineering roles, and focus on teamwork make him a highly compatible candidate for the position.\n\n**Recommendation**:\nI highly recommend considering Sohidul Islam for an interview for the Software Engineering position. His solid technical skills, relevant experiences, and positive attitude towards collaboration make him a strong contender for the role. Furthermore, his background in UI/UX design and problem-solving abilities could bring additional value to the development team."
}
```

## 6. Generate Product Description.

- API Endpoint:

```
{{base_url}}/v1/workflow/generate_visual_product_description
```

- body (Payload)

```json
{
  "url": "https://klevere-pdf-storage.s3.eu-central-1.amazonaws.com/chat-logo.png",
  "amountValue": 1,
  "outputLanguage": "English"
}
```

- Response

```json
{
  "success": true,
  "data": "Hey there, friend! What I've got for you today isn't just a letter, it's the start of something special. This isn't any old 'K'—it's a bold statement. Are you looking for a sleek, modern touch in your space? Something that grabs attention and says, \"I'm all about style\"? Well, you're looking right at it. \n\nThis 'K' is more than just a letter; it's a piece of art. Crafted with crisp lines and balanced design, it stands out with its minimalist yet striking presence. It's the perfect way to personalize your room, office, or even brand your creative space. Imagine this eye-catching monogram greeting guests as they enter—it's sure to spark conversations and ignite curiosity.\n\nThe black and white palette means it'll fit seamlessly no matter your decor, adding that touch of sophistication. And it's not just about looks—this 'K' speaks to those who value design, identity, and expression.\n\nSo, are you ready to make a statement that no one will forget? Add this stunning 'K' to your life and let it be the signature piece that represents the cool, chic, and creative you. Go on, you know you want to!"
}
```

## 7. Enhance Website Headline

- API Endpoint:

```
{{base_url}}/v1/workflow/generate_web_headline
```

- body (Payload)

```json
{
  "product": "Software",
  "points": "Sotware",
  "audience": "IT experts",
  "tone": "conversational",
  "socialMedia": "",
  "amountValue": 1,
  "outputLanguage": "English"
}
```

- Response

```json
{
  "success": true,
  "data": "1. Elevate Your IT Game: The Software That Speaks to Experts.\n2. Experts, Meet Your New Secret Weapon in Tech!\n3. IT Gurus: Discover Software That Gets You.\n4. The Conversational Solution to Your Tech Challenges!\n5. Tech Experts: Simplify Your Work with Smart Software.\n6. Crack the Code to IT Success: Expert-Approved Software Awaits!\n7. Navigate Your IT World with Precision: Expert Software Inside.\n8. Converse with Code: Where Software Meets Mastery.\n9. IT Mastery is Just a Click Away - See How!\n10. Join the IT Elite: Experience the Software Evolution!"
}
```

## 8. Create Social Media Caption

- API Endpoint:

```
{{base_url}}/v1/workflow/generate_visual_social_media_caption
```

- body (Payload)

```json
{
  "url": "https://klevere-pdf-storage.s3.eu-central-1.amazonaws.com/coping-with-pressure-of-job-hunting.jpg",
  "socialMedia": "",
  "amountValue": 1,
  "outputLanguage": "Hindi"
}
```

- Response

```json
{
  "success": true,
  "data": "\"Ever had one of those days where you feel like you've boxed up your motivation with last year's winter clothes? 😅 Hang in there, friends, we all get a little 'wrapped up' sometimes. #JustOneOfThoseDays #UnboxingMotivation\""
}
```

## 9. Create Ad Content

- API Endpoint:

```
{{base_url}}/v1/workflow/generate_digital_advertising
```

- body (Payload)

```json
{
  "product": "Software development",
  "points": "Software",
  "audience": "Student",
  "action": "Learn Programming",
  "tone": "conversational",
  "socialMedia": "",
  "amountValue": 1,
  "outputLanguage": "English"
}
```

- Response

```json
{
  "success": true,
  "data": "Hey there, student! Ready to dive into the world of software development? Start coding with our intuitive software and unleash your potential. Let's learn programming together!"
}
```

## 10. Write Product Description

- API Endpoint:

```
{{base_url}}/v1/workflow/generate_product_description
```

- body (Payload)

```json
{
  "product": "Provide Medical Service",
  "points": "Medical Product",
  "audience": "Student",
  "tone": "conversational",
  "socialMedia": "",
  "amountValue": 1,
  "outputLanguage": "English"
}
```

- Response

```json
{
  "success": true,
  "data": "Hey there, students! Looking for top-notch medical services? Our medical product ensures you get the care you need quickly and conveniently. Say goodbye to long waits and hello to quality healthcare!"
}
```

## 11. Send Webpage Feedback

- API Endpoint:

```
{{base_url}}/v1/workflow/generate_website_feedback
```

- body (Payload)

```json
{
  "output_language": "English",
  "website": "https://vjudge.net/",
  "goal": "Competitve programming"
}
```

- Response

```json
{
  "success": true,
  "data": "### Summary of the Website and Services Offered:\n\nVirtual Judge provides a unique platform that aggregates competitive programming problems from various online judges into a single interface. It allows users to practice on problems sourced from over 40 online judges and submit solutions to be judged on those platforms indirectly. This mechanism facilitates holding contests without the need to access test data directly or rely on a single source for competitive programming challenges. The site aims to serve as a comprehensive tool for practicing and honing competitive programming skills by offering a wide variety of problems across different difficulty levels and topics.\n\n### Positive Feedback:\n\n1. **Aggregation of Problems:** Virtual Judge's strength lies in its aggregation of problems from a vast array of online judges, providing users with unparalleled access to a diversified pool of programming challenges. This variety helps programmers to practice and excel in a broad spectrum of topics.\n2. **Convenience:** The platform simplifies the process of finding and working on problems by centralizing access. This removes the need for users to have accounts on multiple platforms or to navigate through different interfaces and standards.\n3. **Contest Hosting Feature:** Allowing users to host their contests using problems from various sources without the need for original test data is a highly beneficial feature. It boosts competitive programming practices and community engagement by offering a seamless contest creation experience.\n\n### Negative Feedback:\n\n1. **User Experience (UX):** The website's UX might not be as polished or intuitive as some of the individual platforms it aggregates. This can deter new users or frustrate existing ones, particularly those not yet familiar with competitive programming norms.\n2. **Branding and Recognition:** While aggregating problems, Virtual Judge may miss out on establishing a strong brand identity. It runs the risk of being seen merely as a portal rather than a standalone authority in competitive programming.\n3. **Feedback and Learning Resources:** The platform might lack direct, interactive feedback mechanisms and learning resources that individual judges offer. This could limit learners' growth by not providing enough context or guidance on improving their skills.\n\n### Improvements:\n\n1. **Enhance UX and Interface:** Invest in design research to make the website more user-friendly. Implementing a modern, intuitive UI that guides users through problem selection, contest participation, and progress tracking can vastly improve user engagement.\n2. **Develop Unique Content:** Start creating unique educational content, like tutorials, tips for competitive programming, and problem-solving strategies. This not only aids in branding but also adds value for users, making Virtual Judge a go-to resource beyond just problem aggregation.\n3. **Interactive Feedback System:** Integrate an interactive feedback system where users can receive hints or explanations for challenging problems. Additionally, incorporating a community-driven forum for discussing problems and strategies could foster a more engaging learning environment.\n4. **SEO and Content Marketing:** To address visibility, Virtual Judge should optimize its content for search engines through strategic use of keywords related to competitive programming. Moreover, engaging in content marketing by publishing articles, problem-solving guides, and success stories can boost its online presence.\n5. **Partnerships and Collaborations:** Forge partnerships with educational institutions and competitive programming communities. These collaborations can aid in brand recognition and establish Virtual Judge as a pivotal component of the competitive programming ecosystem."
}
```

## 12. Improve Email Subject Line

- API Endpoint:

```
{{base_url}}/v1/workflow/generate_subject_lines
```

- body (Payload)

```json
{
  "product": "Develop software",
  "points": "Sofware",
  "audience": "CSE student",
  "tone": "conversational",
  "socialMedia": "",
  "amountValue": 1,
  "outputLanguage": "English"
}
```

- Response

```json
{
  "success": true,
  "data": "1. \"Transform Your Coding Skills\"\n2. \"Upgrade Your Software Game\"\n3. \"Master Software Development\"\n4. \"Boost Your Coding Knowledge\"\n5. \"Elevate Your Programming Skills\"\n6. \"Unleash Your Coding Potential\"\n7. \"Enhance Your Software Abilities\"\n8. \"Revolutionize Your Coding Techniques\"\n9. \"Optimize Your Software Skills\"\n10. \"Empower Your Coding Journey\""
}
```

## 13. Create Sales Proposal

- API Endpoint:

```
{{base_url}}/v1/workflow/generate_sales_proposal
```

- body (Payload)

```json
{
  "points": "longevity",
  "goal": "Shoes",
  "maker": "Parents",
  "socialMedia": "",
  "amountValue": 1,
  "outputLanguage": "English"
}
```

- Response

```json
{
  "success": true,
  "data": "Dear Parents,\n\nI understand that finding the perfect pair of shoes for your child can be a challenge. With so many options available, it can be overwhelming to know which one will provide the best fit, comfort, and durability.\n\nAt our store, we have been helping families like yours for many years. Our longevity in the industry has given us the expertise to understand the pain points that parents face when shopping for shoes for their children.\n\nWe know that you want to ensure that your child has a comfortable and supportive pair of shoes that will last through all their daily activities. That's why we offer a wide selection of high-quality footwear that is both stylish and durable.\n\nBy choosing our store, you can trust that you are making the best decision for your child's footwear needs. Our team of experienced professionals is here to help you find the perfect pair of shoes that will meet your child's needs and exceed your expectations.\n\nThank you for considering us for your child's shoe shopping needs. We look forward to helping you find the perfect pair of shoes for your little one.\n\nSincerely,\n[Your Name]"
}
```

## 14. Generate Ice Breaker

- API Endpoint:

```
{{base_url}}/v1/workflow/ice_breaker
```

- body (Payload)

```json
{
  "linkedin_url": "https://linkedin.com/in/sishufol",
  "first_name": "Sohidul",
  "undefined": "",
  "socialMedia": "",
  "amountValue": 1,
  "outputLanguage": "English"
}
```

- Response

```json
{
  "success": true,
  "data": "Hi Sohidul,\nI noticed on your LinkedIn profile that you recently started a new role as a Software Engineer at Mediusware Ltd. Congratulations on this exciting career move!"
}
```

## 15. Create Job Description

- API Endpoint:

```
{{base_url}}/v1/workflow/generate_job_description
```

- body (Payload)

```json
{
  "title": "Software engieneer",
  "socialMedia": "",
  "amountValue": 1,
  "outputLanguage": "English"
}
```

- Response

```json
{
  "success": true,
  "data": "Job Title: Software Engineer\n\nCompany Overview:\nWe are a cutting-edge technology company dedicated to creating innovative solutions for the digital age. Our team of passionate individuals is driven to push the boundaries of what is possible in the world of software development. As a Software Engineer at our company, you will have the opportunity to work on exciting projects that will shape the future of our industry.\n\nPosition Overview:\nWe are seeking a talented and experienced Software Engineer to join our dynamic team. The ideal candidate will have a strong passion for technology and a knack for problem-solving. You will be responsible for designing, developing, and implementing software solutions that meet the needs of our clients and customers. This is a great opportunity for individuals who thrive in a fast-paced, collaborative environment and are eager to make a positive impact on the world through technology.\n\nKey Responsibilities:\n- Collaborate with cross-functional teams to design and develop software solutions\n- Write clean, efficient, and maintainable code using best practices and modern technologies\n- Conduct thorough testing and debugging to ensure the quality of the software\n- Update and maintain existing software applications to meet changing business needs\n- Provide technical support and guidance to team members as needed\n- Stay current on emerging technologies and trends in software development\n\nQualifications:\n- Bachelor's degree in Computer Science, Engineering, or related field\n- Proven experience as a Software Engineer or similar role\n- Strong proficiency in programming languages such as Java, C++, or Python\n- Experience with software development tools and frameworks\n- Solid understanding of software development lifecycle and methodologies\n- Ability to work independently and collaboratively in a team environment\n- Excellent problem-solving and communication skills\n\nBenefits:\n- Competitive salary and benefits package\n- Opportunities for professional growth and advancement\n- Vibrant and inclusive work culture that promotes collaboration and creativity\n- Flexible work schedule and remote work options\n- Access to cutting-edge technologies and resources to support your development\n\nJoin our team and be a part of something truly extraordinary. Apply now to become a Software Engineer and help us shape the future of technology. We look forward to welcoming you to our team!"
}
```

## 16. Create Job Description

- API Endpoint:

```
{{base_url}}/v1/workflow/generate_job_description
```

- body (Payload)

```json
{
  "title": "Software engieneer",
  "socialMedia": "",
  "amountValue": 1,
  "outputLanguage": "English"
}
```

- Response

```json
{
  "success": true,
  "data": "Job Title: Software Engineer\n\nCompany Overview:\nWe are a cutting-edge technology company dedicated to creating innovative solutions for the digital age. Our team of passionate individuals is driven to push the boundaries of what is possible in the world of software development. As a Software Engineer at our company, you will have the opportunity to work on exciting projects that will shape the future of our industry.\n\nPosition Overview:\nWe are seeking a talented and experienced Software Engineer to join our dynamic team. The ideal candidate will have a strong passion for technology and a knack for problem-solving. You will be responsible for designing, developing, and implementing software solutions that meet the needs of our clients and customers. This is a great opportunity for individuals who thrive in a fast-paced, collaborative environment and are eager to make a positive impact on the world through technology.\n\nKey Responsibilities:\n- Collaborate with cross-functional teams to design and develop software solutions\n- Write clean, efficient, and maintainable code using best practices and modern technologies\n- Conduct thorough testing and debugging to ensure the quality of the software\n- Update and maintain existing software applications to meet changing business needs\n- Provide technical support and guidance to team members as needed\n- Stay current on emerging technologies and trends in software development\n\nQualifications:\n- Bachelor's degree in Computer Science, Engineering, or related field\n- Proven experience as a Software Engineer or similar role\n- Strong proficiency in programming languages such as Java, C++, or Python\n- Experience with software development tools and frameworks\n- Solid understanding of software development lifecycle and methodologies\n- Ability to work independently and collaboratively in a team environment\n- Excellent problem-solving and communication skills\n\nBenefits:\n- Competitive salary and benefits package\n- Opportunities for professional growth and advancement\n- Vibrant and inclusive work culture that promotes collaboration and creativity\n- Flexible work schedule and remote work options\n- Access to cutting-edge technologies and resources to support your development\n\nJoin our team and be a part of something truly extraordinary. Apply now to become a Software Engineer and help us shape the future of technology. We look forward to welcoming you to our team!"
}
```

## 17. Conduct Hiring Research

- API Endpoint:

```
{{base_url}}/v1/workflow/generate_hiring_research
```

- body (Payload)

```json
{
  "mainPoint": "Software developement",
  "socialMedia": "",
  "amountValue": 1,
  "outputLanguage": "English"
}
```

- Response

```json
{
  "success": true,
  "data": "Sure, I am interested in joining your company for software development. I have experience in languages such as Java, Python, and JavaScript, as well as familiarity with various frameworks and tools. I am confident in my ability to contribute effectively to your team and help drive successful software projects."
}
```

## 18. Create Personalized Hire Letter

- API Endpoint:

```
{{base_url}}/v1/workflow/generate_hire_letter
```

- body (Payload)

```json
{
  "title": "software engineer",
  "undefined": "",
  "socialMedia": "",
  "amountValue": 1,
  "outputLanguage": "English"
}
```

- Response

```json
{
  "success": true,
  "data": "Dear [Candidate],\n\nI am thrilled to extend an offer to you for the position of Software Engineer at our company. Your exceptional skills and experience make you a perfect fit for our team, and we are excited about the possibility of you joining us.\n\nAs a Software Engineer, you will have the opportunity to work on cutting-edge projects and contribute to the development of innovative solutions that will make a real impact on our business. Your expertise in [specific programming languages or technologies] will be a valuable asset to our team, and we are confident that you will thrive in our fast-paced and dynamic work environment.\n\nIn addition to the challenging and rewarding work you will be doing, you will have access to a competitive salary and benefits package, as well as opportunities for professional development and growth within the company. We value our employees and foster a supportive and inclusive work culture that promotes collaboration, creativity, and excellence.\n\nWe are excited about the prospect of you joining our team and are looking forward to the positive impact you will make on our organization. Please let us know if you have any questions or concerns, and we will be happy to address them.\n\nSincerely,\n\n[Your Name]  \nHuman Resources Manager  \n[Company Name]"
}
```

## 19. Notify Employees Termination

- API Endpoint:

```
{{base_url}}/v1/workflow/generate_termination_letter
```

- body (Payload)

```json
{
  "title": "Software engineer",
  "socialMedia": "",
  "amountValue": 1,
  "outputLanguage": "English"
}
```

- Response

```json
{
  "success": true,
  "data": "Dear [Employee's Name],\n\nAfter careful consideration and evaluation of your performance, it is with great regret that we must inform you of our decision to terminate your employment as a Software Engineer at [Company Name], effective immediately.\n\nYour work on various projects and tasks has not consistently met the expectations and requirements of the role, despite efforts to provide additional training and support. We have closely monitored your progress and have determined that your performance does not align with the standards set by our organization.\n\nThe decision to terminate your employment was not made lightly, but rather after thorough review and consideration of all relevant factors. We believe this is the best course of action for both the company and yourself.\n\nPlease be aware that this decision is final and there will be no opportunity for reinstatement. We will provide you with all necessary information regarding your final paycheck, benefits, and any other relevant matters in a separate communication.\n\nWe appreciate the contributions you have made during your time with us and wish you the best in your future endeavors.\n\nSincerely,\n\n[Your Name]\n[Title]\n[Company Name]"
}
```
