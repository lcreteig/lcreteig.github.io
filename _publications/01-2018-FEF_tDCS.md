---
layout: single
title: "No Evidence That Frontal Eye Field tDCS Affects Latency or Accuracy of Prosaccades"
excerpt: "Electrical brain stimulation of the frontal eye fields did not influence reaction time and accuracy of human eye movements"
header:
  teaser: assets/images/publications/2018-FEF_tDCS/2018-FEF_tDCS.png
sidebar:
  - title: "Reference"
    image: assets/images/publications/2018-FEF_tDCS/2018-FEF_tDCS.png
    text: "Reteig LC, Knapen T, Roelofs FJFW, Ridderinkhof KR and Slagter HA (2018). No Evidence That Frontal Eye Field tDCS Affects Latency or Accuracy of Prosaccades. *Front. Neurosci. 12:617*."
  - title: "Full text"
    text: "[Journal website](https://doi.org/10.3389/fnins.2018.00617)"
  - title: "Preprint"
    text: "[bioRxiv](https://doi.org/10.1101/351304)"
  - title: "All other resources"
    text: "[Open Science Framework](https://doi.org/10.17605/OSF.IO/8JPV9)"
  - title: "Data"
    text: "[figshare](https://doi.org/10.21942/uva.6462770)"
  - title: "Code"
    text: "[GitHub](https://github.com/lcreteig/sacc-tDCS)"
---

Modern electrical brain stimulation techniques have an exciting potential (pun intended): they can influence activity of brain cells from outside of the skull. Transcranial direct current stimulation (tDCS) in particular is increasingly being used to try to enhance cognitive processes, such as attention[^1].

In this study, we took that claim to the test and applied tDCS to the frontal eye field---an important area in the spatial attention network of the brain.

We know from earlier work that the frontal eye fields can direct attention to a particular side of space. Specifically, the frontal eye field in the brain's right hemisphere mostly directs attention to the left side of the visual field (and vice versa for its counterpart in the left hemisphere). Also, we know the frontal eye field is responsible for initiating eye movements[^2]. Once the activity of certain frontal eye field neurons reaches a threshold, an eye movement is made, again to the opposite side of the visual field.

Armed with this knowledge, we can make a straightforward prediction how tDCS of the frontal eye field should affect eye movements. With anodal tDCS, we assume that the excitability of neurons is mostly enhanced. This would cause frontal eye field neurons to become a little more active, thus reaching the threshold for evoking an eye movement a little bit sooner than they otherwise would. Therefore, the time it takes to initiate the eye movement should go down.

In fact, this prediction is so straightforward that [an earlier study](https://doi.org/10.3389/fpsyt.2012.00045)[^3] already tried to test it. They found exactly that: after people received anodal tDCS (e.g. to the right frontal eye field), they became faster at making eye movements to the opposite side (e.g. directed to the left visual field).

However, the size of the effect they found was fairly modest: people got about 6 milliseconds faster due to the stimulation. In addition, this was the first study to show that tDCS could indeed have this effect. Therefore, we thought it was a good idea to conduct a very similar experiment, to see if we would get the same outcome.

Unfortunately, we did not. The results we obtained are shown in the figures below.

<figure class="half">
    <a href="/assets/images/publications/2018-FEF_tDCS/FEF_latency_mean.png"><img src="/assets/images/publications/2018-FEF_tDCS/FEF_latency_mean.png"></a>
    <a href="/assets/images/publications/2018-FEF_tDCS/FEF_latency_baseline.png"><img src="/assets/images/publications/2018-FEF_tDCS/FEF_latency_baseline.png"></a>
    <figcaption>Anodal tDCS over the right frontal eye field did not appear to influence eye movement response time.</figcaption>
</figure>

In the left panel, the y-axis shows participants' response time from the moment they had to make an eye movement[^4]. Using an eye tracker, we measured this response time at four different time points (shown on the x-axis): before we switched on the stimulation (_baseline_), during the stimulation (_tDCS_), and two more blocks after the stimulation had completed (_post_)[^5].

The 26 individuals that participated in the study are shown in colored lines. Some are a lot faster than others, and the way their response time changes over the four time points is also highly variable. The black line shows the average effect across the group.

What we expected to see is a decrease in response time during tDCS and afterwards. However, the average line looks fairly flat. This is a little easier to appreciate in the right panel, where we  subtracted the response time at the baseline time point from the subsequent three. Now the graph shows how the response time changed during/after the stimulation, compared to before the stimulation. On average, these changes were minute---less than 1 millisecond.

All in all, our results do not seem to support the effect we expected anodal tDCS to have. We used Bayesian statistics to quantify how much evidence we had for an effect of tDCS or not. This showed that our results are about 5 times more likely when you assume that tDCS had no effect, compared to when you assume that there is a real effect of tDCS.

This is just one result---we looked at a lot of other conditions (see the article for the details):

* We compared these results obtained under anodal tDCS to when participants received cathodal stimulation, which should have the opposite effect on frontal eye field neurons (making them _less_ excitable instead of more).
* We also looked specifically at very fast and very slow eye movements, instead of the average speed.
* We lastly examined the accuracy of eye movements: how close the eye movement landed to the target location, and how much spread there was in these landing points over time.

However, also in these other conditions, we find no consistent effects of tDCS.

The million-dollar question is then of course: why did we not find the expected result, especially given this earlier study that already showed it? Unfortunately, that question has no definitive answer.

One place to start is that we did not do an exact replication of the earlier study. We made a number of changes to the design of the experiment, as detailed in the table below. In principle, any (combination) of these changes could be the culprit. Some we argue are clear improvements; others could be reasonable candidates to explain the difference. For instance, we slightly changed the placement of the electrodes, which could have in turn changed the path of current flow through the brain.

<figure>
    <a href="/assets/images/publications/2018-FEF_tDCS/table_differences.jpg"><img src="/assets/images/publications/2018-FEF_tDCS/table_differences.jpg"></a>
    <figcaption>[Click to enlarge]. Table with differences between original and our study (Table 4 in the article).</figcaption>
</figure>

Interestingly, [a later study](https://core.ac.uk/download/pdf/158976488.pdf)[^6] also took a very similar approach, and did not change the placement of the electrodes as we did, but still found no effect of tDCS.

Therefore, it's also possible that the changes we made were not decisive. Rather, the initial study could have overestimated the size of the tDCS effect. In reality, it might take a larger study with a possibly even more optimal stimulation protocol to show whether the effect is truly there.

For now, we conclude it remains uncertain whether tDCS of the frontal eye field can be used to improve spatial attention. Our experiment is not the only one that failed to confirm earlier findings. In fact, the article is published in a [Research topic at  the journal "Frontiers in Neurosience"](https://www.frontiersin.org/research-topics/5535/non-invasive-brain-stimulation-effects-on-cognition-and-brain-activity-positive-lessons-from-negativ) that brings together a couple dozen studies where tDCS did not have any effect.

As an individual scientist, it's never fun if the study you worked long and hard on doesn't pay off. However, we have to take such null results seriously, as they might indicate that our initial ideas about tDCS were too optimistic. The hope is that the research field can collectively learn "positive lessons from these negative findings", to design more successful studies in the future.

[^1]: See our [previous review paper]({{"publications/02-2017-Review_tES_attention" | relative_url }}) on this topic.
[^2]: The frontal eye fields were actually "discovered" through electrical stimulation back in the 19th century, when David Ferrier observed that monkeys made an eye movement when he applied electrical microstimulation directly to this area of the brain.
[^3]: Kanai, R, Muggleton, NG and Walsh V (2012). Transcranial direct current stimulation of the frontal eye fields during pro-and antisaccade tasks. _Frontiers in Psychiatry, 3_, 45. doi: 10.3389/fpsyt.2012.00045
[^4]: To be more specific, they were fixating in the middle of a computer screen, and then a target stimulus (black dot) suddenly appeared either to the left or right. The eye movement response time (or _saccade latency_) is then defined as the time between (1) the onset of this target and (2) the onset of the eye movement.
[^5]: Each of these time points is an average of around 15 minutes, in which the participant was performing the eye movement task.
[^6]: Chen, PL and Machado, L (2017). Developing clinically practical transcranial direct current stimulation protocols to improve saccadic eye movement control. _Journal of Eye Movement Research, 10(3)_, 5. doi:10.16910/jemr.10.3.5
