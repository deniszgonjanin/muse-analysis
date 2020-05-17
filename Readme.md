Analyzing data from the [Muse headband](https://choosemuse.com/)

I've been meditating for a long time, and I wanted to try out the Muse headband, which analyzes your EEG while you meditate and provides you with auditory neuro-feedback so that you can improve your meditation. For example, it plays the sound of bird song when your mind is 'calm' and the sound of rain when your mind is 'active'. After each session using the headband and the [app](https://play.google.com/store/apps/details?id=com.interaxon.muse&hl=en_CA), it would show you a graps of your mind activity, and an score indexes based on how active/neutral/calm your mind was.

Anecdotally, I could tell that it works. During some sessions, while my mind was calm I would hear a lot of birds chirping, and when my mind started getting distracted, I would hear a lot or rain. It felt really good allowing my mind to just 'be' while the birds are chirping, and really try to re-engage my focus when rain was falling.

However, during some sessions rain would fall constantly even when I felt my mind was pretty calm. During others, birds would chirp constantly no matter what I did.

While I liked using it, I started wondering if I could somehow measure how accurate it is, beyond my qualitative day-to-day experience.

The analysis contained in this repo is the result of that effort. I decided to do a simple experiment:

- Every day I used the Muse, I would sit down for 2 sessions, back to back.
- Each of the sessions would be 10 minutes in length
- After the first session, I would shut down the [Muse app](https://play.google.com/store/apps/details?id=com.interaxon.muse&hl=en_CA), and shut down the headband.
- I would then re-open the app, turn on the headband, and record the second session.
- Afterwards, I recorded the app's index scores for both of the sessions.

My thinking was that there should be some sort of relationship between the first session's score and the second. By recording the sessions back to back, I could get as close as I could to a controlled experiement. My state of mind would be the same, so there should be some correlation between the first session score and the second session score.

So far, I have recorded about 30 session-pairs of data, which is not enough for a statistically significant test. I continue to record the data, which you can find in the 'data.csv' file in this repo. The analysis is found in the jupyter notebook.

