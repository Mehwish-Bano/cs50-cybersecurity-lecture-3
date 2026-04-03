💻 Practical Examples – Securing Software

🔹 Phishing Example

<a href="https://fake.com">https://trusted.com</a>

---

🔹 XSS Example

<script>alert('Hacked')</script>---

🔹 Escaped Output

<script>alert('safe')</script>

---

🔹 SQL Injection Example

Input:
' OR '1'='1

Query becomes:
SELECT * FROM users WHERE username='' OR '1'='1'

---

🔹 Safe Query (Prepared Statement)

SELECT * FROM users WHERE username = ?

---

🔹 CSRF Example

<form action="https://example.com" method="POST">
<input type="hidden" name="action" value="buy">
</form><script>
document.forms[0].submit();
</script>---

🔹 Secure Practice Summary

✔ Validate input
✔ Escape output
✔ Use prepared statements
✔ Implement CSRF tokens
✔ Avoid trusting client-side data

---
