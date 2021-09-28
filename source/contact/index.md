---
title: Contact Us
---

<style>
    .article-date {
        display: none;
    }
</style>

<br>

<form action="https://robust.flg360.co.uk/api/APIHTTPPost.php" method="post">
<input type="hidden" name="intLeadGroupID" value="54553" />
<input type="hidden" name="strSource" value="" />
<input type="hidden" name="strMedium" value="" />
<input type="hidden" name="strTerm" value="" />
<input type="hidden" name="intSiteID" value="15334" />
<input type="hidden" name="intReferrerBuyerID" value="0" />
<input type="hidden" name="intDPAStatusPhoneID" value="1">
<input type="hidden" name="intDPAStatusSMSID" value="1">
<input type="hidden" name="intDPAStatusEmailID" value="1">
<input type="hidden" name="strAPISuccessURL" value="http://www.robustittraining.com/thankyou" />
<input type="hidden" name="strAPIFailURL" value="http://www.robustittraining.com/sorry" />
<input type="hidden" name="strLeadData2" value="Lead is from blog/contact/" />

  <div class="mb-3">
    <label for="name" class="form-label">Your firstname *</label>
    <input type="text" name="strLeadFirstName" id="strLeadFirstName" placeholder="" required="required" class="form-control" />
  </div>
  <div class="mb-3">
    <label for="surname" class="form-label">Your lastname *</label>
    <input type="text" name="strLeadLastName" id="strLeadLastName" placeholder="" required="required" class="form-control" />
  </div>
  <div class="mb-3">
    <label for="email" class="form-label">Your email *</label>
    <input type="email" name="strLeadEmail" id="strLeadEmail" placeholder="" required="required" class="form-control" />
  </div>
  <div class="mb-3">
    <label for="phone" class="form-label">Phone Number *</label>
    <input type="number" name="strLeadPhone1" id="strLeadPhone1" placeholder="" required="required" class="form-control" />
  </div>
  <div class="mb-3">
    <label for="message" class="form-label">Your message for us </label>
    <textarea rows="4" name="strLeadData4" id="strLeadData4" placeholder="Enter your message" class="form-control"></textarea>
  </div>
  <button type="submit" class="btn btn-primary">Submit</button>
</form>

  <br>
