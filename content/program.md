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

Abstract: Multimodal communication on social media platforms is immensely complex. Especially the popular format of short video content is making use of many different semiotic modes that operate in various interrelated ways. Moreover, stories on Instagram and videos on TikTok do not always only present a narrative, but often also embed argumentative or instructional structures or use metaphors, metonymies or other rhetorical figures to convey meaning. Identifying these structures and creating new and reasonable communicative artefacts with a similar complexity currently represents one of the main challenges for computational and AI tools. 
In this presentation, I will provide ways of using recent developments from multimodality research to address this challenge interdisciplinarily. I will particularly show how frameworks for the multimodal analysis of discourse relations (and the discursive structure of such complex communication) can help identify more and relevant details of human understanding and with this build a stronger basis for further computational research. The aim is to show both theoretical (i.e. semiotic and logical) and methodological insights for the analysis of cross-modal relations as well as their applicability for larger corpus and computational analyses. 

Bio: Janina Wildfeuer is a #multimodalist with a multi-faceted background in linguistics, semiotics, and discourse analysis. She has about 15 years of experience in working with visual and audiovisual communication and has built particular expertise in films and audiovisual data, comics, social media and games. Janina has contributed to the theoretical and methodological development of multimodality studies and also worked in corpus-analytical and empirically oriented projects. At the moment, she focuses on the question of how (audio-)visual communication can help building a better future for our society. In her position at the University of Groningen, Janina teaches classes on multimodality, digital communication, visual and audio-visual analysis and works as programme coordinator of the Master program Communication and Information Studies. She is also the Chief Editor of the journal 'Visual Communication', one of the key journals in the field of visual and multimodal communication, and Associate Editor for the speciality section 'Multimodality of Communication' with Frontiers in Communication.

- 15:00-15:30 - Break
- 15:30-16:00 - Invited talk by Eric Müller-Budack “Multimodal News Analytics”
- 16:00-17:00 - Keynote by Desmond Elliott “Towards Multilingual and Multimodal Language Processing for Everyone”

Abstract: Multimodal research has typically focused on English language understanding and reasoning, due to the limited availability of multilingual datasets. In this talk, I will speak about the importance of multilingual multimodal processing from two perspectives. In the first perspective, I will describe how we can create high-quality non-English multimodal datasets in culturally-engaged processes. From the second perspective, I will discuss the role of tokenization-free language modelling in enabling high-quality and lightweight multilingual representations for all written languages.

Bio: Desmond is an Associate Professor and a Villum Young Investigator at the University of Copenhagen. He obtained his Ph.D from the University of Edinburgh, under the supervision of Frank Keller, and he was a Postdoctoral Researcher at CWI, and the University of Amsterdam in the Netherlands. His current research interests include tokenisation-free language modelling, and multilingual and multimodal learning. He received the EMNLP 20201 Best Long Paper Award for creating the multicultural MarVL dataset, and he has been involved in the creation of several other multilingual multimodal datasets, including Multi30K, How2, and the IGLUE benchmark.

- 17:00-17:30 - Invited talk by Chihaya Matsuhira “Data-Driven Approaches for Modeling Human Perception of Nonwords”
- 17:30-17:50 - Accepted talk by Yusuke Hirota et al. “Mitigating Gender Bias in Zero-Shot Image Captioning Models”
- 17:50-17:55 - Closing session

