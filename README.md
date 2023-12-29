# Audio-Emotion-Analysis

### Pre-defined Questions and our pre-defined hypotheses:
- Do sentiments (opinion or view) differ from emotions?
Hypothesis: It should differ as some emotions can be positive but have a negative
sentiment.

- Are both these the same or different?
Hypothesis: Both these emotions and sentiments are different

- How does emotion evolve throughout the movie?
Hypothesis: Since the movie is about Anne Frank, it should have a lot of sad emotions

- Does the length of the sentence have anything to do with the emotions and sentiments?
Hypothesis: The length of sentences should be independent of emotions or sentiments,
as both of these can be expressed in a single word.

- Do sentences combined have different emotions and sentiments compared to a single
sentence?
Hypothesis: Sentences combined have different emotions and sentiments.


### Data Used:
Two datasets were used:
- First is audio file(MP3) of "ANNE FRANK’s DIARY- Animated feature film" taken from youtube.
- Second dataset taken from Kaggle - "Emotions dataset for NLP"

### Models Used:
- Whisper AI used for converting the first dataset into text and then breaking this text into sentences. Then this is converted to dataframe forming a new dataset
- Neural Network trained on the second dataset(accuracy of 99.7%). The new dataset obtained from above is then given as input in this model in order to get the emotions.
- Textblob model used for getting the sentiments from the sentences which were formed in 1st point.

After this, different python libraries and modules were used in order to get answers to above given pre-defined questions with some visualization to verify the proof.

### Some Visualizations:
#### Sentiment Distribution
![image](https://github.com/kalp1202/Audio-Emotion-Analysis/assets/76723038/0e174582-b666-46ab-8e3f-a4a68725927f)

#### Emotion Analysis
![image](https://github.com/kalp1202/Audio-Emotion-Analysis/assets/76723038/ff9e8046-3d4b-44d5-941e-02842b37dae2)

#### Word Cloud for Joy emotion:
![image](https://github.com/kalp1202/Audio-Emotion-Analysis/assets/76723038/042bce39-f4ad-48bf-ab3b-d08902b9eb17)

#### Word Cloud for Sadness emotion:
![image](https://github.com/kalp1202/Audio-Emotion-Analysis/assets/76723038/b3fc4769-322c-416c-9499-872ca568d5e5)

#### Word Cloud for Fear emotion:
![image](https://github.com/kalp1202/Audio-Emotion-Analysis/assets/76723038/ed2b00c8-b2d6-43b2-8d8f-6ca1ffda5c54)

#### Evolution of emotion throughout the film
![image](https://github.com/kalp1202/Audio-Emotion-Analysis/assets/76723038/5b773b12-52a3-4567-8217-ef715fe94f46)



### Conclusion:
● Do sentiments (opinion or view) differ from emotions?
Observation from different figures determines that sentiments and emotions differ. This again holds then analysis is done for combined sentences which combines neighboring sentences to do analysis. 

● Are both these the same or different?
Observation from different figures show that emotions are similarly distributed across all three sentiments [Positive, Negative, Neutral], and further test result indicates that they are independent of each other.

● How does emotion evolve throughout the movie?
The movie has exhibited 3 emotions according to the model built. Emotion Joy is prevalent at the start of the movie followed by sadness during the middle phase and fear is concentrated towards the end of the movie.

● Do sentences combined have different emotions and sentiments compared to a single
sentence?
The combination of sentences showed that there was no change in the distribution of the emotions but it did show a difference between emotions displayed for 255 out of 1207 entries of sentences. However, in the case of sentiments, there was a change in the distribution. There were also 455 out of 1207 entries of combined sentences which showed a different sentiment than single sentences.

### Future Work:
- Making the spoken words count and thereby creating a smarter system that also consider feelings and not just written text.
- Listening to the emotion of sounds and the way of understanding the acoustic emotions and tones instead of spoken words.
- Seeing the emotion in faces and thereby considering the video as well in consideration for better analysis.
