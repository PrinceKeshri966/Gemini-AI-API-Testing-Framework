# Gemini API Testing with Postman

This project contains a Postman collection used to test and document the Gemini Pro APIs by Google.

## 🔧 APIs Covered
- Generate Text Content
- Multi-modal Input
- Get Embeddings
- Error Handling Cases

## 📦 How to Use
1. Import `Gemini_API_Collection.json` into Postman.
2. Set your environment variables:
   - `PROJECT_ID`
   - `API_KEY` or `BEARER_TOKEN`
3. Run requests and test scripts.

## 🧪 Sample Tests
```javascript
pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});
