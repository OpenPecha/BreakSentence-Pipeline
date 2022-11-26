[![break-sentence](https://github.com/OpenPecha/BreakSentence-Pipeline/actions/workflows/break-sentence.yml/badge.svg)](https://github.com/OpenPecha/BreakSentence-Pipeline/actions/workflows/break-sentence.yml)
# BreakSentence-Pipeline
Pipeline for breaking sentence in text or excel files.

**Pipeline Arechitecture**
![](https://i.imgur.com/uwhpEbu.png)


## Steps for triggering pipeline

1. Check out to `BreakSentence`  branch
2. User push a Text file or a Excel file to path `/BreakSentence/BreakSentence_Input/[Text|Excel]`
3. User can manualy trigger the breakSentence workflow by going to the `Action` section in the repository, then choose the `break-sentence` action on the left side.
4. There are a message shows that "This workflow has a workflow_dispatch event trigger." On the right side, press the `Run workflow` button, and fill the information bellow:
    - source file name
    - source file type
    - source file language. Press the green `Run workflow` button. 
5. Go to "`GitHub User` is calling Azure BreakSentence API." entries.
6. Wait for job complete. Then you can downloadd the BreakSentence_Resulsts in the `Artifacts` section.
