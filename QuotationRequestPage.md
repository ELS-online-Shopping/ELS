# ELS <section class="big_block description">
      <div class="container">
         <div class="col-xs-12">
             <form action="Order.php" method="POST" id="form-redeem">
					<div class="col-lg-6">
						<h3 class="form-section-heading">Event Info</h3>
						<div class="form-row">
							<!-- full name -->
							<label for="name" class="form-label">Full Name</label>
							<input type="text" name="name" id="name" placeholder="* required" class="form-text" required="required">
						</div>
						<div class="form-row">
							<!-- email address -->
							<label for="email" class="form-label">Email</label>
							<input type="email" name="email" id="email" placeholder="* required" class="form-text" required="required">
						</div>
						<div class="form-row">
							<label class="form-label">What day(s) is your event?</label>
							<div class="row">
								<div class="col-lg-4">
									<label for="date1" class="form-label">Start Date:</label>
									<input type="text" name="date1" id="date1" class="form-text useDatePicker calendar-icon">
								</div>
								<div class="col-lg-4">
									<label for="date2" class="form-label">End Date:</label>
									<input type="text" name="date2" id="date2" class="form-text useDatePicker calendar-icon">
								</div>
								 
							</div>
						</div>
						<div class="form-row">
							<!-- List in order the areas of greatest importance -->
							<label for="event-time" class="form-label">Event Time</label>
							<textarea name="event-time" id="event-time" class="form-text"></textarea>
						</div>
						<div class="form-row">
							<!-- how do we gain entrance? -->
							 
						</div>
						<div class="form-row">
							<!-- voucher number -->
							<label for="number-of-guests" class="form-label">Number of Guests</label>
							<input name="number-of-guests" id="number-of-guests" class="form-text">
						</div>
						<div class="form-row">
							<!-- Dates of service requests? -->
							<label for="additional-details" class="form-label">Additional Details</label>
							<textarea name="additional-details" id="additional-details" class="form-text"></textarea>
						</div>
					</div>
					<div class="col-lg-6">
						<h3 class="form-section-heading">Location Info</h3>
						<div class="form-row">
							<label for="physical_address" class="form-label">Physical Address</label>
							<input class="form-text" id="physical_address" name="physical_address" placeholder="Enter location, starting with street number..." required="required" autocomplete="off">
						</div>
				
						<div class="form-row">
							<label for="" class="form-label">City</label>
							<input class="form-text" id="locality" name="city" required="required">
						</div>
						<div class="form-row">
							<label for="" class="form-label">Region</label>
							<input class="form-text" id="administrative_area_level_1" name="state" required="required">
						     <select type="text" id="region" name="region" >
  <option value="caprivi">Caprivi</option>
  <option value="erongo">Erongo</option>
  <option value="hardap">Hardap</option>
  <option value="ohangwena">Ohangwena</option>
  <option value="Oshana">Oshana</option>
  <option value="Oshikoto">Oshikoto</option>
  <option value="otjozondjupa">Otjozondjupa</option>
  </select>
                                                </div>
						 
					</div>
					<div class="row">
						<div class="col-xs-12 text-center">
							<div class="form-row text-center">
								<div id="recaptcha-container">
									<div class="g-recaptcha" data-sitekey="6LdPjxcUAAAAANQKYDdLiv3TDVz5zP8s5ztb3JCX"><div style="width: 304px; height: 78px;"><div><iframe src="https://www.google.com/recaptcha/api2/anchor?k=6LdPjxcUAAAAANQKYDdLiv3TDVz5zP8s5ztb3JCX&amp;co=aHR0cDovL2JsdXNhZ2VjYXRlcmluZy5jb206ODA.&amp;hl=en&amp;v=r20170411114922&amp;size=normal&amp;cb=6ggatnj3rw2v" title="recaptcha widget" width="304" height="78" frameborder="0" scrolling="no" name="undefined"></iframe></div><textarea id="g-recaptcha-response" name="g-recaptcha-response" class="g-recaptcha-response" style="width: 250px; height: 40px; border: 1px solid #c1c1c1; margin: 10px 25px; padding: 0px; resize: none;  display: none; "></textarea></div></div>
								</div>
							</div>
							<div class="form-row">
								<input type="submit" id="submit-button" class="form-btn" value="Submit">
							</div>
						</div>
					</div>
				<input type="hidden" name="intent" value="redeem">
				<input type="hidden" name="url" value="">
			</form>
			
		</div>
      </div>
   </section>
