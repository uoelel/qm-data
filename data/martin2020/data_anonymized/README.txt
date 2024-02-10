README for suffixing preference similarity judgment experiment

Stimuli are syllables or shapes. Task is 2AFC. There are 2 practice trials, and 42 test trials. Within the test trials are 25 critical trials with pre- and post-changed stimuli and the two choices. There are an additional 15 catch trials with correct answers (indicated), 3 each of:
- pre + identical (identical)
- post + identical (identical)
- pre + different (pre)
- post + different (post)
- identical + different (identical)

English data (English_anon.csv)

condition: {shapes, syllables}
subjID: anonymous ID
phase: {test} (practice phrase responses are not provided)
trial: trial number
trial_type: {ident-post, ident-pre, post-diff, pre-diff, pre-post} (see above for details)
target: description of target sequence
correct_order: {1,2} button number of the correct response 
correct: description of correct sequence (post is correct for pre-post trials)
wrong: description of wrong sequence (pre is wrong for pre-post trials)
strategy: written comments provided by participant
strategy_coded: {no_strategy, beginning}
lang1: self-reported language knowledge (1)
lang1_rating: {1-10} (self-reported rating of language 1 knowledge)
lang2: self-reported language knowledge (2)
lang2_rating: {1-10} (self-reported rating of language 2 knowledge)
lang3: self-reported language knowledge (3)
lang3_rating: {1-10} (self-reported rating of language 3 knowledge)
lang4: self-reported language knowledge (4)
lang4_rating: {1-10} (self-reported rating of language 4 knowledge)
response: {1,2} button number of participant response
accuracy: {1,0} binary coding of participant reponse accuracy for trial
catch_accuracy: overall proportion correct responses for participant across all catch trials (same value will therefore be repeated on each trial for a given participant)

Kîîtharaka data (Kiitharaka_anon.csv)

subjID: anonymous ID
condition: {shapes, syllables}
phase: {test} (practice phrase responses are not provided)
target: description of target sequence
correct_choice: description of correct sequence (post is correct for pre-post trials)
wrong_choice: description of wrong sequence (pre is wrong for pre-post trials)
correct_order: {1,2} button number of the correct response 
trial_type: {ident-post, ident-pre, post-diff, pre-diff, pre-post} (see above for details)
response: {1,2} button number of participant response
accuracy: {1,0} binary coding of participant reponse accuracy for trial
catch_accuracy: overall proportion correct responses for participant across all catch trials (same value will therefore be repeated on each trial for a given participant)