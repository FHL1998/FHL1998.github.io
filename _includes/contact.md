<h2 style="margin: 60px 0px 10px;">Contact</h2>

<div class="contact-grid" style="display: grid; grid-template-columns: minmax(0, 1fr) 100px; gap: 24px; align-items: start; margin-top: 12px;">
  <div class="contact-details">
    <div>65 Nanyang Dr, Singapore 637460</div>
    <div>Phone: <a href="tel:+6585153028">(+65) 85153028</a>/ <a href="tel:+14244289189">(+1) 424-428-9189</a></div>
    <div>Office: <a href="https://maps.app.goo.gl/BHKPS163hPMqXngD7">Industrial Robotics Lab N3-01B-09</a></div>
  </div>

  {% if site.mapmyvisitors_id %}
  <div class="contact-map" style="width:100px; justify-self:end;">
    <a href="https://mapmyvisitors.com/web/{{ site.mapmyvisitors_id }}" target="_blank" rel="noopener noreferrer">
      <img src="https://mapmyvisitors.com/map.png?d={{ site.mapmyvisitors_id }}&amp;cl=ffffff" alt="Visitor map">
    </a>
  </div>
  {% endif %}
</div>
