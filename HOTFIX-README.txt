Option Pricer v3.0.3 input-validation hotfix

Replace docs/app.js and docs/index.html in the repository, commit, and push to main.

Root cause corrected:
The validation function incorrectly applied Number.isFinite() to the option-type string ('call' or 'put'). This caused every otherwise valid input set to fail validation.

Verification completed:
- JavaScript syntax check passed.
- The displayed default case (S=96, K=105, T=1, r=4.5%, q=1.2%, volatility=28%, steps=200, call, European) passed the corrected validation test.
- index.html now requests version 3.0.3 to bypass cached JavaScript.
