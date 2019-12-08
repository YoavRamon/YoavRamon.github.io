---
layout: post
title:  "Speaker Diarization with Kaldi"
date:   2019-02-28 14:00:00 +0200
categories: updates medium
---
In most real-world scenarios speech does not come in well defined audio segments with only one speaker. In most of the conversations that our algorithms will need to work with, people will interrupt each other and cutting the audio between sentences won’t be a trivial task.

In addition to that, in many applications we will want to identify multiple speakers in a conversation, for example when writing a protocol of a meeting. For such occasions, identifying the different speakers and connect different sentences under the same speaker is a critical task.

Speaker Diarization is the solution for those problems. With this process we can divide an input audio into segments according to the speaker’s identity. It can be described as the question “who spoke when?” in an audio segment.

You can read the rest of the article at [Medium](https://towardsdatascience.com/speaker-diarization-with-kaldi-e30301b05cc8)
