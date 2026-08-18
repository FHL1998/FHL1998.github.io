<h2 style="margin: 60px 0px 10px;">Contact</h2>

<div class="contact-grid" style="display: grid; grid-template-columns: minmax(0, 1fr) 180px; gap: 24px; align-items: start; margin-top: 12px;">
  <div class="contact-details">
    <div>65 Nanyang Dr, Singapore 637460</div>
    <div>Email: <a href="mailto:haolin.fan@ntu.edu.sg">haolin.fan@ntu.edu.sg</a> / <a href="mailto:e0816265@u.nus.edu">e0816265@u.nus.edu</a></div>
    <div>Phone: <a href="tel:+6585153028">(+65) 85153028</a>/ <a href="tel:+14244289189">(+1) 424-428-9189</a></div>
    <div>Office: <a href="https://maps.app.goo.gl/BHKPS163hPMqXngD7">Industrial Robotics Lab N3-01B-09</a></div>
  </div>

  {% if site.mapmyvisitors_widget_token %}
  <div class="contact-map" style="width:130px; justify-self:end;">
    <script type="text/javascript" id="mmvst_globe" src="https://mapmyvisitors.com/globe.js?d={{ site.mapmyvisitors_widget_token }}&amp;w=a"></script>
  </div>
  {% endif %}
</div>
