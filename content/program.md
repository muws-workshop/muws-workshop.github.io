---
title: "Program"
---

## Time zones

- Phuket Time: <span id="phuket-time"></span>
- Central European Time: <span id="berlin-time"></span>

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

**Time**: 13:30-18:25 Phuket Time

**Room**: Dara, Dusit Thani Laguna Phuket

- 13:30-13:35 - Welcome session
- 13:35-14:05 - Invited talk by Tianwei Chen “Would Deep Generative Models Amplify Bias in Future Models?”
- 14:05-15:00 - Keynote by Janina Wildfeuer “The complex (discourse) structures of multimodal communication: are they really computable?”
- 15:00-16:00 - Break
- 16:00-17:00 - Keynote by Desmond Elliott “TBD”
- 17:00-17:30 - Invited talk by Chihaya Matsuhira “Data-Driven Approaches for Modeling Human Perception of Nonwords”
- 17:30-18:50 - Accepted talk by Yusuke Hirota et al. “Mitigating Gender Bias in Zero-Shot Image Captioning Models”
- 18:50-18:20 - Invited talk by Eric Müller-Budack “Multimodal News Analytics”
- 18:20-18:25 - Closing session

