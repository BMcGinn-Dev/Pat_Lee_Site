title: Contact me
subtitle: Please...
image: /static/images/people_bw.jpg


# Contact Information

## Email
<a href="mailto:myemail@gmail.com" target="_blank">myemail@gmail.com</a>

## Facebook
<a href="https://www.facebook.com/myfacebook" target="_blank">https://www.facebook.com/myfacebook</a>

## More
Check the social icons at the footer to know where else I can be found!

-------------------------------------

<form id="contact-form" name="contact-form" action="https://formsubmit.co/bensdevjourney@gmail.com" method="POST">
    <!-- Hidden fields -->
    <input type="hidden" name="_subject" value="Mr. Lee, You have a new submission!">
    <input type="hidden" name="_next" value="https://google.com">
    <div class="left">
        <label for="name" class="" style="color: black;" >Enter your name</label>
    </div>
    <div class="right">
        <textarea type="text" id="name" name="name" rows="1" cols="25" placeholder="Name" required></textarea>
    </div>
    <br>
    <div class = "left">
        <label for="email" class="" style="color: black;">Enter your email</label>
    </div>
    <div class="right">
        <textarea type="text" id="email" name="email" rows="1" cols="25" placeholder="Email" required></textarea>
    </div>
    </br>
    <div class="right">
        <label for="subject" class="" style="color: black;" >Subject</label>
    </div>
    <div class="left">
        <textarea type="text" id="subject" name="subject" rows="1" cols="25" placeholder="Subject" required></textarea>
    </div>
    </br>
    <div class="left">
        <label for="message" style="color: black;">Your message</label>
    </div>
    <div class="right">
        <textarea type="text" id="message" name="message" rows="5" cols="50" placeholder="Message" required></textarea>
    </div>
    </br>
    <!-- Here is the button -->
    <div class="center isolated">
        <button class="button" type="submit">Send</button>
    </div>
</form>


<!-- Button

<div class="center isolated">
    <a class="button" href="{{url_for('static', filename='images/lake3_branding.jpg')}}" target="_blank">GOOD PLACE TO WORK</a>
</div> 

-->

