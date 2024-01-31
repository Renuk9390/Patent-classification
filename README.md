<h2>Patent classification&nbsp;</h2>
<hr />
<p>This project is aiming to implement the patent classification at the subclass level<br />according to IPC and CPC systems. The total number of classes is more than 600.</p>
<p>The pipeline for the project implementation is as below:</p>
<ol>
<li>Extract dataset</li>
<li>EDA of the dataset</li>
<li>Train a model&nbsp;</li>
</ol>
<p>For all of the above tasks, the respective jupyter notebook is shared.</p>
<p>With the Google big query, the dataset for the classification task is generated. The generated dataset is stored in the CSV file. For each year varying from the year, 2009 to 2019 separate CSV files are created. This dataset is made publically available for experiment purposes. The attribute of these CSV files are as shown in the table below:</p>
<table style="border-collapse: collapse; width: 93.63%; height: 57px;" border="1">
<tbody>
<tr style="height: 18px;">
<td style="width: 3.36176%; text-align: center; height: 18px;"><strong>ID</strong></td>
<td style="width: 7.60389%; text-align: center; height: 18px;"><strong>Date</strong></td>
<td style="width: 14.7257%; text-align: center; height: 18px;"><strong>Title</strong></td>
<th style="width: 14.1694%; height: 18px;">Claim</th>
<td style="width: 8.70241%; text-align: center; height: 18px;"><strong>cpc_subclass</strong></td>
</tr>
<tr style="height: 39px;">
<td style="width: 3.36176%; text-align: center; height: 39px;">8844051</td>
<td style="width: 7.60389%; text-align: center; height: 39px;">2014-09-23</td>
<td style="width: 14.7257%; text-align: center; height: 39px;">Lithium-ion secondary battery</td>
<td style="width: 14.1694%; text-align: left; height: 39px;">A lithium-ion secondary battery comprising ...</td>
<td style="width: 8.70241%; text-align: center; height: 39px;">H01M,Y02E,Y02T</td>
</tr>
</tbody>
</table>
<p>The link to download this dataset by year is provided below.</p>
<ul style="list-style-type: circle;">
<li>2009 CSV <a href="https://drive.google.com/file/d/1G--5oT0eNzZM2L02Zhd2hd9nNGu75TWk/view?usp=drive_link">Link</a></li>
<li>2010 CSV <a href="https://drive.google.com/file/d/14hNeUALys3ZFVbtxwcXytECZHqv7YxDI/view?usp=drive_link">Link</a></li>
<li>2011 CSV <a href="https://drive.google.com/file/d/15mkhHcEJ13m_k-1RoOEahtVsGSVe-L5d/view?usp=drive_link">Link</a></li>
<li>2012 CSV <a href="https://drive.google.com/file/d/12GuuEB_jMD3lnpCNEidyOUK_o00l6lrD/view?usp=drive_link">Link</a></li>
<li>2013 CSV <a href="https://drive.google.com/file/d/1tJwkYP5XzinVZjzhIvRWDVHI1RXj9ud8/view?usp=drive_link">Link</a></li>
<li>2014 CSV <a href="https://drive.google.com/file/d/11Bb2qHUnc70I2v-MwTA6jDZaeOz1Mi-m/view?usp=drive_link">Link</a></li>
<li>2015 CSV <a href="https://drive.google.com/file/d/1zrz63TlU0P3u48CmP-wmlHezAGlilbgu/view?usp=drive_link">Link</a></li>
<li>2016 CSV <a href="https://drive.google.com/file/d/1YrRWOvtfASv51vDAvUA47h7aFzFRk9X6/view?usp=drive_link">Link</a></li>
<li>2017 CSV <a href="https://drive.google.com/file/d/1R3JgxZDb43SWG5qdd73roNYJAGYeJs-N/view?usp=drive_link">Link</a></li>
<li>2018 CSV <a href="https://drive.google.com/file/d/1hyCF0_oMXDGiau1oVmSRhii-NCtjCcFv/view?usp=drive_link">Link</a></li>
<li>2019 CSV <a href="https://drive.google.com/file/d/1emELGF1uDmCRMMAzivV89ExCqFf3lI6v/view?usp=drive_link">Link</a>&nbsp;</li>
</ul>
<p><img src="https://html-online.com/editor/tiny4_9_11/plugins/emoticons/img/smiley-smile.gif" alt="smile" /></p>

 

