# Lab 7 - Unit & E2E Testing

**Names:** Yanhua Liu

## ✅ Check Your Understanding

1) **Where would you fit your automated tests in your Recipe project development pipeline?**

**Answer:** Within a GitHub action that runs whenever code is pushed.  
**Reason:** This approach automates testing, ensuring any code changes don’t break existing functionality before merging. It keeps the pipeline safe and avoids relying on human discipline alone.

---

2) **Would you use an end-to-end test to check if a function is returning the correct output?**

**Answer:** No.  
**Reason:** E2E tests focus on user interactions and workflows across the app. Unit tests are better suited for verifying specific function outputs.

---

3) **What is the difference between navigation and snapshot mode in Lighthouse?**

**Answer:**  
- **Navigation mode:** Runs after page load and measures performance during the initial load of a full page.  
- **Snapshot mode:** Captures a static view of the page in its current state, mainly useful for finding accessibility issues or static layout problems.

---

4) **Three things to improve the CSE 110 shop site based on Lighthouse results:**
- Optimize image sizes and formats
- Minimize render-blocking resources (e.g., scripts and CSS)
- Improve accessibility by fixing missing labels and contrast issues

## ✅ Running Tests

To run all the tests:

```bash
npm install
npm run test
```
## 📸 Test Results Screenshot

![Test Results](https://github.com/BoscoLiu0/Lab7_Starter/blob/main/npm_test.jpg?raw=true)
