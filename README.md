# Javascript
javascript code for email validation <br>
function validateEmail(email) {
    // Regular expression for validating email
    const emailPattern = /^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,}$/;

    // Test the email against the pattern
    if (emailPattern.test(email)) {
        return true;  // Valid email
    } else {
        return false;  // Invalid email
    }
}

// Example usage
const email = "user@example.com";
if (validateEmail(email)) {
    console.log("Valid email!");
} else {
    console.log("Invalid email!");
}
