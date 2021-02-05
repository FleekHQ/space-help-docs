---
date: "1"

---
<script>
  window.intercomSettings = {
    app_id: "ywevvpcu"
  };
</script>

<script>
// We pre-filled your app ID in the widget URL: 'https://widget.intercom.io/widget/ywevvpcu'
(function(){var w=window;var ic=w.Intercom;if(typeof ic==="function"){ic('reattach_activator');ic('update',w.intercomSettings);}else{var d=document;var i=function(){i.c(arguments);};i.q=[];i.c=function(args){i.q.push(args);};w.Intercom=i;var l=function(){var s=d.createElement('script');s.type='text/javascript';s.async=true;s.src='https://widget.intercom.io/widget/ywevvpcu';var x=d.getElementsByTagName('script')[0];x.parentNode.insertBefore(s,x);};if(w.attachEvent){w.attachEvent('onload',l);}else{w.addEventListener('load',l,false);}}})();
</script>

## Email Not Available or Uses Different Sign in Method
Did you receive this error while trying to sign into your Space account? This can mean two things:

- **Option A:** The email is invalid or not available.
- **Option B:** The email is valid, but it has been registered with a different sign-in method than the one you are using/trying.

## Option B: Email is valid, but Uses Different Sign in Method
Emails in Space are unique to all accounts, **no matter how you choose to sign in (Twitter, Gmail, Email, etc.)**. 

If you registered an account with automatic Twitter sign-in option, then the email associated to that Twitter account will be considered in-use, and you won't be able to create a new account using -for example- the Gmail sign-in option using that same address.

To avoid security risks, you **can't sign into your account with a sign-in method that hasn't been configured yet**. 

This means that, that if you created a Space account using the Twitter sign-in button, and that Twitter account uses the email john@gmail.com, you won't be able to use the Gmail sign-in button, or request an email magic link, **unless it has been previously configured in your account's settings as a backup/extra sign in option.**

This helps avoid scenarios such as:

1. You sign-up using Twitter.
2. An attacker gains access to the email linked to your Twitter.
3. The attacker request a magic link, and accesses your account without needing your Twitter.

If you are certain this is the email you used to create your Space account, try recalling the sign-in method you originally used for it: Twitter, Gmail, Email, etc. And, once you are back inside your account, configure an additional sign-in option to avoid this trouble in the future.

## Want to add a secondary sign-in option?
Read the [following guide](https://help.space.storage/getting-started/adjusting-settings/) on how to add an alternative/backup sign in option to avoid these errors, and have an emergency way of accessing your account in the future.



