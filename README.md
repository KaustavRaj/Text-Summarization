# Text Summarizer

Here I have implemented a _text summarizer_ based on **Amazon Fine Food Reviews** dataset, which is kept in **/data** section as "_Reviews.csv_" and can also be found on kaggle.
The **Text Summarization** jupyter notebook contains the entire code of how I implemented the abstractive text summarizer model.

Further more, a manual bearing the name **Text Summarization Manual** is also given for using the trained model easily.

#### Evaluation metric
I have used Rouge score for evaluating model's accuracy, and it obtains the following rouge scores (*rounded off to two decimal places*). The detail code for it in given in **Evaluation Metric** notebook.

<table>
<tbody>
<tr>
<td></td>
<td>f1 score</td>
<td>precision</td>
<td>recall</td>
</tr>
<tr>
<td>Rouge-1</td>
<td>0.28</td>
<td>0.33</td>
<td>0.27</td>
</tr>
<tr>
<td>Rogue-2</td>
<td>0.12</td>
<td>0.14</td>
<td>0.12</td>
</tr>
<tr>
<td>Rogue-l</td>
<td>0.26</td>
<td>0.32</td>
<td>0.26</td>
</tr>
</tbody>
</table>
