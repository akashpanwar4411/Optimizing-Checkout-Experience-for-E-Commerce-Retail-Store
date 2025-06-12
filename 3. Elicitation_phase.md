# Elicitation Phase Deliverables – Optimizing Checkout Experience

## 1. Elicitation Notes

**Objective:**  
To gather detailed insights from stakeholders regarding current pain points and desired improvements in the checkout process.

**Elicitation Methods Used:**
- One-on-one interviews with Product Owner and UX Lead
- Observation of user sessions and customer support logs
- Surveys sent to recent users who abandoned carts
- Review of analytics tools (e.g., Hotjar, Google Analytics)

**Key Observations:**
- Users abandon checkout when asked to create an account (friction)
- Lack of guest checkout is a major barrier
- Mobile form fields are difficult to navigate
- Long loading times between checkout steps
- Limited payment options, especially mobile wallets

---

## 2. Stakeholder Feedback Summary

| **Stakeholder**     | **Role**              | **Feedback Highlights**                                                                 |
|---------------------|------------------------|------------------------------------------------------------------------------------------|
| Product Owner       | Business Lead          | Wants to increase completed purchases by making checkout seamless and fast              |
| UX Designer         | UI/UX Improvement      | Emphasized need for mobile-first redesign and fewer clicks to complete purchase         |
| Developer Lead      | Tech Feasibility       | Concerned about third-party dependencies and recommends phased deployment               |
| Customer Support    | Frontline Feedback     | Frequent complaints about 'forced login', unclear error messages                        |
| QA Analyst          | Testing Readiness      | Wants better test cases for mobile variations and form validation                       |

---

## 3. Initial Requirements List (High-Level)

| **Req. ID** | **Requirement Description**                                              | **Type**         | **Priority** |
|-------------|---------------------------------------------------------------------------|------------------|--------------|
| RQ-001      | Allow guest checkout without mandatory login                             | Functional       | High         |
| RQ-002      | Redesign checkout to reduce steps from 5 to 3                             | Functional       | High         |
| RQ-003      | Optimize mobile form layout for faster data entry                        | Non-Functional   | Medium       |
| RQ-004      | Add support for mobile payment wallets (e.g., GPay, Paytm)               | Functional       | Medium       |
| RQ-005      | Show progress bar during checkout                                        | UX/Functional    | Low          |
| RQ-006      | Provide clearer validation error messages on input fields                | Functional       | High         |
| RQ-007      | Improve load speed of checkout page to under 2 seconds                   | Non-Functional   | High         |
