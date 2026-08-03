# API Security Risk Analysis (Modern SaaS Skill)

## 📌 Project Overview
This project was completed as part of the **Future Interns Cyber Security Internship**.

The objective of this project is to perform a **read-only API Security Risk Analysis** on a public API, identify common security risks, assess authentication and access control, and provide recommendations to improve API security.

This project focuses on security assessment and documentation only. No exploitation or unauthorized testing was performed.

---

## 🎯 Objective

- Analyze a public API safely.
- Inspect API requests and responses.
- Review authentication and authorization.
- Identify common API security risks.
- Classify risks based on severity.
- Recommend security best practices.

---

## 🛠 Tools Used

- Postman
- Google Chrome
- JSONPlaceholder API
- Microsoft Word
- GitHub

---

## 🌐 API Tested

**JSONPlaceholder**

https://jsonplaceholder.typicode.com/

Endpoint Tested:

GET /posts

---

## 🔍 Methodology

1. Selected the JSONPlaceholder public API.
2. Sent GET requests using Postman.
3. Inspected API responses.
4. Reviewed request and response headers.
5. Checked authentication requirements.
6. Identified potential security risks.
7. Documented findings and recommendations.

---

## ⚠️ Identified Security Risks

- Publicly accessible endpoint
- No authentication required
- No visible rate limiting
- Sample data exposure

---

## 📊 Risk Assessment

| Risk | Severity |
|-------|----------|
| Public Endpoint | Medium |
| Missing Authentication | Medium |
| No Visible Rate Limiting | Low |
| Sample Data Exposure | Low |

---

## 💼 Business Impact

- Unauthorized access to public resources
- Potential API abuse
- Increased security risk if implemented in production
- Possible service disruption without rate limiting

---

## ✅ Recommendations

- Implement JWT or OAuth authentication.
- Enable rate limiting.
- Validate user inputs.
- Encrypt sensitive data.
- Use HTTPS.
- Monitor API activity with logging.

---

## 📷 Screenshots

Screenshots are available in the **screenshots/** folder.

- GET Request
- API Response
- Headers
- Authorization
- JSONPlaceholder Homepage
- Browser JSON Response

---

## 📂 Project Structure

```
API_Security_Risk_Analysis/
│
├── README.md
├── API_Security_Risk_Analysis_Report.pdf
├── API_Security_Risk_Analysis_Report.docx
├── API_Security_Risk_Analysis_Presentation.pptx
└── screenshots/
```

---

## 📚 References

- https://jsonplaceholder.typicode.com/
- https://owasp.org/API-Security/
- https://www.postman.com/

---

## 👨‍💻 Author

**Tamil Selvan**

Future Interns – Cyber Security Internship

---

## 📄 License

This project is created for educational purposes as part of the Future Interns Cyber Security Internship.
