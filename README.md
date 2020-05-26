# NTM_EN_DE_ATTENTION
This repo is about the NTM from German to English. <br>
<em><b>Dataset</b></em>: English and German dataset downloaded from Spacy, which is tokenized and transferred to lower cases. Then they are splited into train, validation and test dataset. <br>
<em><b>Encoder</b> </em>and <em><b>Decoder</b></em>: GRU, attention and masking are applied<br>
<em><b>BLEU score</b></em>: around 29<br>
<em><b>Visualization</b> </em>of the result:<br>
src is the input of German sentences and trg is the groud truth, and prd is the prediction. <br>
<img align='center' style="border-color:gray;border-width:2px;border-style:dashed"  src="prediction_example.png" width = "600px" height="550px" ></img>
