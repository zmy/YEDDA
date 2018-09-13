YEDDA: A Lightweight Collaborative Text Span Annotation Tool
======

Use as an annotator 
====
* Generate TextQuestionBrief json file by using ExtractTextQuestion.cs in the Test assmbly of FormsInsights Project.
* Start the interface: run `python YEDDA_Annotator.py`
* Choose the json file "****.json" you want to annotate by clicking the Open button.
* Select a phrase in the answer text widget, then click either a letter (a-z) or a digit (0-9) to annotate it as a key phrase for the current text question
* To delete an annotation, select the annotated phrase with the format '[@key phrase@], then click either a letter (a-z) or a digit (0-9) to delete it from the key phrases for the current text question
* At most five answers for a text question can be presented at once. Click Next or Back button to see next or previous five answers, respectively.
* To export the annotation, click the Export button and a json file "***_labeling.json" will be generated.


Important features:
=====
1. Key phrases for a text question will be shown in the Label Result: window.
2. Annotated phrase is presented as "[@phrase@]"
3. When a phrase is annotated as key phrase, all the same phrases in the answers will be annotated automatically.

