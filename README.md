# Counterbalanced Stroop task and emotional Stroop task

#### Files in this repository were used to conduct an experiment involving the Stroop task and emotional Stroop task. The experiment was creating using the PsyToolKit framework.

## Setup on your own PsyToolKit account
#### Start by creating a new survey and 2 new experiments. In my case, I named the experiments *Emotion_Standard_Stroop* and *Standard_Emotion_Stroop* for the counterbalancing conditions. If you wish to use different names, then you will need to adjust the *survey.txt* counterbalancing section to match with your experiment names.

### Survey
##### Simply upload *survey.txt* into your own survey project.

### Experiments
##### Upload all the necessary files into the experiment tab. These should include:
<ul> 
    <li>/images *</li>
    <li>experiment_file.psy **</li>
    <li>words_negative.txt</li>   
    <li>words_neutral.txt</li>   
    <li>words_positive.txt</li>   
    <li>words_standard.txt</li>   
</ul>

#### Notes:
<ul> 
    <li>* You cannot directly upload a folder into the experiment menu on PsyToolKit. Instead, you must first create a separate folder within the files folder of the experiment. You can then upload all the image files into this new folder.</li>
    <li>** The experiment file should correspond to whichever counterbalancing condition you are creating. For example, if you are creating the emotion Stroop first condition, then use the experiment_emo_stan.psy file. <b>DO NOT upload both .psy files into the same experiment tab.</b></li>
    <li>Due to the <i>include</i> function used in the experiment file, the word text files must be in the same folder as the experiment file. This is why the word files are not in a subdirectory in this repository.</li>
</ul>