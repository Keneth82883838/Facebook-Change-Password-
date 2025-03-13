# Facebook-Change-Password-<!doctype html>
<html lang="en"> 
 <head> 
  <meta charset="UTF-8"> 
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> 
  <title>Change Password | Facebook</title> 
  <link rel="stylesheet" href="style.css"> 
 </head> 
 <body> 
  <div class="modal"> 
   <div class="modal-content"> 
    <h2>Change password</h2> 
    <p>Your password must be at least 6 characters and should include a combination of numbers, letters, and special characters (!@$%@).</p> 
    <form id="changePasswordForm"> <!-- Current Password --> 
     <div class="input-container"> 
      <input type="password" id="currentPassword" placeholder="Current password" required> <span class="toggle-password" onclick="togglePassword('currentPassword')">👁️</span> 
     </div> <!-- New Password --> 
     <div class="input-container"> 
      <input type="password" id="newPassword" placeholder="New password" required> <span class="toggle-password" onclick="togglePassword('newPassword')">👁️</span> 
     </div> <!-- Confirm New Password --> 
     <div class="input-container"> 
      <input type="password" id="confirmPassword" placeholder="Re-type new password" required> <span class="toggle-password" onclick="togglePassword('confirmPassword')">👁️</span> 
     </div> <!-- Forgot Password Link --> <a href="#" class="forgot-password">Forgot your password?</a> <!-- Checkbox --> 
     <div class="checkbox-container"> 
      <input type="checkbox" id="logoutDevices"> <label for="logoutDevices">Log out of other devices. Choose this if someone else used your account.</label> 
     </div> <!-- Submit Button --> <button type="submit">Change password</button> 
     <p id="message"></p> 
    </form> 
   </div> 
  </div> 
  <script src="script.js"></script> 
 </body>
</html>