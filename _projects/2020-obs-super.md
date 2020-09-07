---
layout: project
title: Observational Supervision 
subtitle: Using Passively Observed Human Signals To Improve Medical Imaging Architectures
---

<img style="width: 40%; float: left; border: 1px solid black; margin-top: 10px; margin-right: 10px;" src="{{"/assets/projects/obs-super.png" | prepend: site.baseurl }}"/>
**Overview:** 

Medical Imaging blha blah


Medical imaging is a compelling application area for supervised machine learning methods. Convolu- tional Neural Networks (CNNs) in particular have recently achieved promising results on applications ranging from cancer diagnosis (Esteva et al., 2017) to radiograph worklist prioritization (Dunnmon et al., 2018); however, these results rely on massive hand-labeled datasets. This requirement for large hand-labeled datasets - which are expensive, because they require physician time to create - has hampered efforts to deploy these models to improve clinical outcomes.
To reduce this labeling cost, we explore rich observational signals that can be passively collected at annotation time, such as eye tracking (or “gaze”) data, which describes where a person has looked while performing a task (Barrett et al., 2018; Rodríguez et al., 2018). This approach is possible because of recent advances in eye tracking technology, which has quickly transformed from a technique that was intrusive, inaccurate, and expensive into one that is viable for real-time gaze data collection (Fu et al., 2016). Inspired by the success of eye tracking techniques in NLP applications that only use gaze signal at train time (Hollenstein & Zhang, 2019), we examine a straightforward mapping of gaze data to visual attention layer activations in a way that encourages the model to draw influence from the same spatial regions most heavily utilized by the human annotator.
