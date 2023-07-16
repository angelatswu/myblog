---
title: "Contact Me"
date: 2023-07-16T12:46:02-04:00
draft: false
---

Have questions or feedback? Contact me below. 

{{< rawhtml >}}
<style>
    div {
        margin-bottom: 10px;
    }
    label {
        display: inline-block;
        width: 200px;
        text-align: right;
    }
</style>

<form action="https://api.web3forms.com/submit" method="POST">
    <input type="hidden" name="access_key" value="c5c3b45f-87fa-464a-895d-6320433e2e44">
<div>
    <label>Name:</label>
    <input type="text" id="name" name="name" required>
</div>
<div>
    <label>Email:</label>
    <input type="email" id="email" name="email" required>
</div>
    <textarea name="message" required cols="30" rows="10">What's on your mind?</textarea>
    <button type="submit">Submit Form</button>
</form>
{{< /rawhtml >}}