# API Documentation of Klevere Ai

```
{{baseUrl}} = http://127.0.0.1:5000/api
```

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

# API Documentation of Klevere Ai

```
{{baseUrl}} = http://127.0.0.1:5000/api
```

## 2. Performance Evaluation

- API Endpoint:

```
{{base_url}}/v1/workflow/generate_performance_evaluation
```

- body (Payload)

```json
{
  "title": "Find out good employee performance",
  "outputLanguage": "English"
}
```

- Response

```json
{
  "success": true,
  "data": "Title: Employee Performance Evaluation Policy\n\nPurpose:\nThe purpose of this policy is to ensure a fair and effective evaluation process for assessing employee performance within the organization.\n\nScope:\nThis policy applies to all employees of the company, regardless of position or tenure.\n\nPolicy:\n1. Regular Evaluation:\n- All employees will undergo regular performance evaluations at least once a year.\n- Managers will assess employee performance based on predetermined criteria and performance goals.\n\n2. Feedback:\n- Employees will receive constructive feedback on their performance and areas for improvement.\n- Managers will provide ongoing feedback to employees to help them reach their full potential.\n\n3. Recognition:\n- High-performing employees will be recognized and rewarded for their achievements.\n- Performance evaluations will be used to identify top performers for advancement opportunities within the organization.\n\n4. Development:\n- Employees will be provided with resources and support to help them improve their performance.\n- Training and development programs will be offered to help employees enhance their skills and knowledge.\n\n5. Documentation:\n- Performance evaluations and feedback will be documented in employee records for future reference.\n- Documentation will be used to track employee progress and determine promotions or disciplinary actions.\n\n6. Confidentiality:\n- Performance evaluations will be kept confidential between managers and employees.\n- Information about employee performance will only be shared on a need-to-know basis.\n\n7. Compliance:\n- All managers and employees are expected to comply with this policy and participate in the performance evaluation process.\n- Any concerns or disputes regarding performance evaluations should be addressed through the appropriate channels.\n\nImplementation:\nThis policy will be communicated to all employees and managers, and training will be provided on the evaluation process. The HR department will oversee the implementation and enforcement of this policy.\n\nReview:\nThis policy will be reviewed and updated periodically to ensure it remains relevant and effective in assessing employee performance.\n\nThis policy is designed to promote a culture of excellence and continuous improvement within the organization. By adhering to these guidelines, we can identify and support our top performers while providing opportunities for all employees to reach their full potential."
}
```
