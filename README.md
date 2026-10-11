# TS-VAP Speech Extraction Demo

[Open the combined demo](https://jjjjiaozi.github.io/TS-VAP/).

Group 1 includes a 12-second IEMOCAP dialogue example selected from the
Session 5 test set. The target speaks before and after the partner, while an
added LibriSpeech third voice runs from 2–12 seconds. It compares USEV,
Acoustic VAP, and MiniOmni VAP using the same mixture and 0.6-second chunks.

The combined page includes a 12-second online-video example in Group 1.
Its [NASA source video](https://commons.wikimedia.org/wiki/File:NASA_Interview_Opportunity-_Ring_of_Fire_THIS_Weekend_With_Annular_Solar_Eclipse_(SVS14424_-_NICHOLEEN_CANNED_INTV_V1).webm)
is a single-speaker interview with an added LibriSpeech voice. The original
soundtrack serves as the target reference. This is a controlled listening
example, not a conversational test-set sample.

Group 2 also includes a 16-second Carrie Brockwell interview with a LibriSpeech voice added from 4–14 seconds. The original soundtrack is the target reference. It compares baseline, History, History + Pred, Sync, and Sync + Pred. Both matched Pred configurations improve over their no-Pred counterparts on this selected excerpt; it is not an aggregate test-set result.

Group 1 also includes three selected Seamless Interaction conversation examples with an added LibriSpeech third voice. One comes from the dataset's dev split and two from its train split; their target reference tracks are speaker-bleed-denoised rather than studio-clean. These are selected listening examples, not held-out test-set aggregate results.
