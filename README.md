Greg Higgins Personal-Project
================

Live Website: www.ambassadorsaz.com

I was asked by a local member of my church to create a website for his campus ministry.  He was very laid back on his guidelines on what he wanted the site to look like, other than stating that it needed to have a clear navigation bar and a minimalist, modern look.  I had only every developed very basic html-only based sites in years previous, but I decided that this would be a good learning opportunity.  Although it may look simple, one of the biggest challenges on this site was the navigation bar on the top right of the page.  Rather than writing them as static, hyperlinked text that is tabbed apart, I decided to take a stab at making a type of "widget" in java to do the job. 

As I neared completion of his site, the owner started talking about ways to implement a type of donation system that was safe and secure.  My suggestion was of course PayPal. Using a mixture of code provided by PayPal and reinventing the wheel a little bit, here was my solution. 
```
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
<html><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8" /><title></title></head><body><form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
<input type="hidden" name="cmd" value="_s-xclick">
<input type="hidden" name="hosted_button_id" value="BW7AM5ZRZVYLQ">
<input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!">
<img alt="" border="0" src="https://www.paypalobjects.com/en_US/i/scr/pixel.gif" width="1" height="1">
</form>
</body></html>
```

I realize that the website isn't by any means the most complicated or intricate thing around, but it is what the owner wanted.  After creating this website, I feel that if I was asked by another individual to do the same, I would feel confident that I could complete the task.
