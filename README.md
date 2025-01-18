# Counterbalanced Stroop task and emotional Stroop task

### Live Demo: https://us.psytoolkit.org/c/3.4.6/survey?s=MsYmQ

#### Files in this repository were used to conduct an experiment involving the standard Stroop task and the emotional Stroop task. The experiment was created using the PsyToolKit framework. The original experiment investigated the effect of rumination and emotional processing on the Stroop task.

## Set up on your own PsyToolKit account

#### Start by creating a new survey and 2 new experiments. In my case, I named the experiments _Emotion_Standard_Stroop_ and _Standard_Emotion_Stroop_ for the counterbalancing conditions. If you wish to use different names, then you will need to adjust the _survey.txt_ counterbalancing section to match with your experiment names.

### Survey

##### Simply upload _survey.txt_ into your own survey project.

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
    <li>** The experiment file should correspond to whichever counterbalancing condition you are creating. For example, if you are creating the emotional Stroop counterbalancing condition, then use the <i>experiment_emo_stan.psy</i> file. <b>DO NOT upload both .psy files into the same experiment tab.</b></li>
    <li>Due to the <i>include</i> function used in the experiment file, the text files for the trial words must be in the same folder as the experiment file. This is why the word files are not in a subdirectory in this repository.</li>
    <li>Since the original experiment involved rumination, you will need to remove any images relating to rumination if you want to use the Stroop task for a different experiment.</li>
</ul>
