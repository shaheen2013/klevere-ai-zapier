# API Documentation of Klevere Ai

## {{baseUrl}}

```
https://app.klevere.ai:5000/api
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
