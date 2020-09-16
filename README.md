# Recognizing-numbers-from-(0-5)-in-sign-language-using-TF
<img src="https://github.com/pdesai878/Recognizing-numbers-from-0-5-in-sign-language-using-TF/blob/master/images/hands.png">

**Expected Output**:

<table> 
    <tr> 
        <td>
            Train Accuracy
        </td>
        <td>
        0.9990741
        </td>
    </tr>
    <tr> 
        <td>
            Test Accuracy
        </td>
        <td>
        0.725
        </td>
    </tr>

</table>

This algorithm can recognize a sign representing a figure between 0 and 5 with 72.5% accuracy.

**Insights**:
- This model seems big enough to fit the training set well. However, given the difference between train and test accuracy, you can try to add L2 or dropout regularization to reduce overfitting. 

