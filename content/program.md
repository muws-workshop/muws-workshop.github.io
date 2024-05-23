---
title: "Program"
---

## Time zones

### Central European Time
<div id="berlin-time"></div>

### Phuket Time
<div id="phuket-time"></div>

<script>
function updateTime() {
  var now = new Date();

  // Berlin time
  var berlinTime = new Intl.DateTimeFormat('en-GB', { 
    timeZone: 'Europe/Berlin', 
    hour: '2-digit', 
    minute: '2-digit', 
    second: '2-digit' 
  }).format(now);

  // Phuket time
  var phuketTime = new Intl.DateTimeFormat('en-GB', { 
    timeZone: 'Asia/Bangkok', 
    hour: '2-digit', 
    minute: '2-digit', 
    second: '2-digit' 
  }).format(now);

  // Update the HTML content
  document.getElementById('berlin-time').textContent = berlinTime;
  document.getElementById('phuket-time').textContent = phuketTime;
}

// Update time immediately and then every second
updateTime();
setInterval(updateTime, 1000);
</script>

## Schedule

**Date**: June 10, 2024 in Phuket, Thailand

**Time**: TBD

**Room**: TBD


